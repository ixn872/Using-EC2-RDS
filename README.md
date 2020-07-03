# Using-EC2-RDS
How to connect a MSSQL RDS instance on an EC2 python application

### Requirements:
* EC2 Instance
* MSSQL RDS Instance

### Instructions:
* Make sure you attach the relevant policies to your user 
* Make sure your Instance is publicly available
* Configure the correct MSSQL protocols for your instance VPC 
* Also look at the EC2 VPC to have access to MSSQL
* Install using pip pymssql


### Documentation I used:

https://www.youtube.com/watch?v=IxorZNEfcMk
https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ConnectToMicrosoftSQLServerInstance.html#USER_ConnectToMicrosoftSQLServerInstance.Security
https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_VPC.Scenarios.html
https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Troubleshooting.html#CHAP_Troubleshooting.Connecting
https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_VPC.WorkingWithRDSInstanceinaVPC.html
