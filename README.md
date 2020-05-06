Creates a server subnet with the ArcGisServer AMI, a DB Subnet with Oracle and SQL Server RDS instances

Prerequisites to run this template:
* a) An AMI ID ready to run ArcGis
* b) existing security groups for the ArcGis Server (RDP/SSH, 6443) and Databases (1521, 1433)
* c) existing VPC
* d) existing keypair to use when connecting to the EC2 ArcGis Server
