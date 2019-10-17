# docker-oracle
## oracle ee 11g with docker  

hostname: localhost  
port: 1521  
sid: EE  
service name: EE.oracle.docker  
username: system  
password: oracle  
## after pull
cd docker-oracle  
mkdir tar  
cd tar  
## upload oracledb-20181227.tar
tar -xvf oracledb-20181227.tar  
mv /u01 /  
cd..  
docker-compose up -d    

