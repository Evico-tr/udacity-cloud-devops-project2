### Name: Emeka Anachebe 
### Programme: Udacity Cloud DevOps Engineer
### Project: Deploy a high availability web app using cloud formation

## Web App Load Balancer URL - http://udagr-webap-lhmpcu0y29i3-663291462.us-east-1.elb.amazonaws.com/

# Network.yml: Template used to create the UdagramNetworkStack
# Network-parameters.json: Contains parameters for the UdagramNetworkStack
# Server.yml: Template used to create the UdagramServerStack
# Server-parameters.json: Contains parameters for the UdagramServerStack

This project deploys a highly available web app to EC2 instances across two availability zones in private subnets. Traffic is routed to these backend servers via a Load Balancer. The EC2 instances were created by an auto-scalling group using a launch configuration that specifies the parameters of the instance, along with the instance profile needed to give the instances access to S3.

The Components created can be seen in the Udagram Infrastructure Diagram.jpeg