# RDS

## RDS Read Replicas

- **Asynchronous replication**

## RDS Read Replicas - Network Cost

- For RDS Read Replicas within **the same region**, you don't pay that fee

## RDS Multi AZ

- **SYNC replication**

## RDS Custom

- **Managed Oracle and MSSQL Server with OS and database customization**
- RDS: Automates setup, operation, and scaling of database in AWS
- Custom: access to the underlying database and OS as you can
  - Configure settings
  - Install patches
  - Enable native features
  - Access the underlying EC2 Instance using SSH or SSM Session Manager
- **De-activate Automation Mode** to perform your customization, better to take a DB snapshot before

## RDS vs RDS Custom

- RDS: entire database and the OS to be managed by AWS
- RDS Custom: full admin access to the underlying OS and the database

## Amazon Aurora

- support only Postgres and MySQL
- Aurora is "AWS cloud optimized", 5x performance improvement over MySQL on RDS and 3x Postgres on RDS
- Aurora automatically grows in increments of disk: 10GB, up to 128TB
- Aurora can have up to 15 replicas, and it is faster than MySQL
- costs more than RDS (~20% more) - but it more efficient
 