# docker-oracle
## oracle ee 11g with docker  

hostname: localhost  
port: 1521  
sid: EE  
service name: EE.oracle.docker  
username: system  
password: oracle  
## after pull
mkdir /u01/app/oracle/data  
or
cd /
tar -xvf oracledb-20181227.tar
cd docker-oracle  
docker-compose up -d  
