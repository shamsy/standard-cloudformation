# standard-cloudformation
Standard CloudFormation template

Prerequisites:
RDS role: rds-monitoring-role need to be created with policy: AmazonRDSEnhancedMonitoringRole attached

Parameters:
AmazonLinuxAMIID
/aws/service/ami-amazon-linux-latest/amzn2-ami-hvm-x86_64-gp2
-
BizVPCCIDR
10.0.0.0/16
-
MasterUsername
admin
-
MasterUserPassword
****
-
ParameterGroup
bizcom247-pg
-
PrivateSubnetparam1
10.0.0.0/18
-
PrivateSubnetparam2
10.0.64.0/18
-
PublicSubnetparam1
10.0.128.0/18
-
PublicSubnetparam2
10.0.192.0/18
-
