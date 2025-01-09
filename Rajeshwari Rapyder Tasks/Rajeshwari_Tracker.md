### Teusday 22-Oct-2024
- [x] AWS Certified Developer Associate Course initiated
- [x] Getting started
- [x] Intro
- [x] IAM & CLI

### Wednesday 23-Oct-2024
- [x] EC2
- [x] ELB
- [x] VPC
- [x] ELS3B

### Thursday 24-Oct-2024
- [x] AWS - CLI, SDK, IAM Roles and Responsibilities
- [x] Serverless, AWS Lambda 
- [x] Syncronous Invocations, services,lambda & ALB(HTTP-JSON, vice versa)
- [x] S3 event notifications, event source mapping,strea,s, queues,error handling, mapper scalling
- [x] permissions, Policies, Eventand Context Objects, Destinations,logging & Monitoring,X-Ray
- [x] customization at Edge, CloudFront Func, Lambda@Edge, Lambda by default, VPC, lambda layers.
- [x] lambda File system Mounting, Concurrency, Ext Dependencies, Lambda & CloudFormation, Container images

### Friday 25-Oct-2024
- [x] AWS Lambda versions, Aliases, CodeDeploy, Function URL & Security, CodeGuru Profiling, Best Practices
- [x] DynamoDB intro, Overview, WCU & RCU - ThroughtPut

##

### Monday 28-Oct-2024
- [x] Revision - IAM,EC2,Load Balancers
- [x] Setup Apache Web Server on EC2 Instance 
- [x] created 2 EC2 instances to see the changes in the updation using bootstrap code for Apache
- [x] created a load balancer for the EC2 and distributed it among them and tested in the browser.

### Teusday 29-Oct-2024
- [x] Redoing yesterday's tasks
- [x] Trouble shooted the problem regarding the target groups
- [x] created Auto Scalling Group for EC2

### Wednesday 30-Oct-2024
- [x] Yesterdays tasks- Creating instances and attaching to a LB and created an Auto Scaling group for it as well.
- [x] AWS Networking Services
- [x] Protocols, Subnetting, CIDR
- [x] OSI Model, TCP/IP, Amazon VPC


##


### Monday 04-Nov-2024
- [x] Recreating a scaled and load-balanced application and revising the Networking Basics
- [x] Created the Presentation Tier of the 3-Tier Architecture
- [x] Task 1 - List S3 buckets using AWS Lambda.
- [x] Task 2 - List the contents of a S3 bucket. (Any bucket)

### Teusday 05-11-2024
- [x] Revising HTTP in TCP/IP, diff btwn WAF, NACL, Security groups
- [x] Created the Presentation Tier of the 3-Tier Architecture
- [x] Task 3 - List any 4 buckets with its contents using random module
- [x] Task 4 - Get the list of all Security Groups inside all the VPCs. Take a VPC that has maximum number SGs.

### Wednesday 06-11-2024
- [x] Successfully created the Presentation Tier of the 3-Tier Architecture.
- [x] Created the Application Tier of the 3-Tier Architecture
- [x] Task 5 - Get the names of each object of the S3 bucket and put in a file in a csv format and put it in a bucket
- [x] Task 6 - Put the names of the SGs that have any port open to 0.0.0.0 in a file.

### Thursday 07-11-2024
- [x] Created the Presentation and the Application Tier of the 3-Tier Architecture.
- [x] Created the DataBAse Tier of the 3-Tier Architecture and completed with the 3-tier arch.
- [x] Task 7 - Created VPC with 2 public and 2 private subnets with different route tables for public and private subnets and  VPC endpoint to S3

### Friday 08-11-2024
- [x] Task 8 - Utilise Event bridge as a trigger for the previous lambda functions.
- [x] Task 9 - Create a bucket and 2 folders. and Upload files to these folders using CLI and console, Configured the bucket to host static website and host sample html page. Created an IAM user who can access only newly created bucket.

##

### Monday 11-11-2024
- [x] Task 1 - Created a Lambda function to list the resources - EC2 ,AWS Lambda ,S3 Bucket ,EC2 Volumes (both types) , VPCs 
- [x] Task 2 - Created a lambda function add tags to all the resources
- [x] Task 3 - Created a lambda function delete tags to all the resources

### TeusDay 12-11-2024
- [x] Completed with Previous Tasks with Rectifing all the errors and replaced S3 with dynamoDB
- [x] Reseraching about API Gateway and the payload request for the next task

### Wednesday 13-11-2024
- [x] Succesfully deletd the VPC - problem( bymistake created a RDS proxy for db security group)
- [x] Task - API Gateway Trigger for your AWS Lambda Function for the Lambda function for task 1. Then, based on the POST payload, the Lambda function will tag the resource. 

### Thursday 14-11-2024
- [x] Created a CloudFormation Template for the similar API Gateway of the Previous Task. 
- [x] Updated the CFT with lambda Function and invoking with API Gateway

### Friday 15-11-2024
- [x] Updated the previous CFT and succesfully it created and rectified the errors as well (PostMEthod - IntegrationResponse, MethodResponse)
- [x] CloudWatch alarm for a EC2 instance, and create alarms on metrics: CPU Utilization & Memory Usage Percentage 

##


### Monday 18-11-2024
- [x] Create the CloudWatch Alarm using AWS Console of the prev Task.
- [x] ecxel task - Spin up an EC2 Instance with Security Group. EC2 instance should have a Tag with you name
- [x] Created a CFT for CloudWatch alarm for a EC2 instance, and alarms on metrics: CPU Utilization & Memory Usage Percentage 

### Teusday 19-11-2024
- [x] Introduction to Amazon DynamoDB for Serverless Architectures,
How it works and Design Considerations.
 - [x] Serverless Architecture Patterns in DynamoDB
 - [x] Amazon DynamoDB - Data Modeling Techniques.

### Wednesday 20-11-2024
- [x] Architecting Serverless Application,Migration Considerations,Data Stores, Application Architecture Patterns
- [x] Event-driven Architecture, Serverless Event Submission Patterns, Patterns for Communicating Status Updates

### Thursday 21-11-2024
- [x] Serverless Data Processing Patterns, with Kenesis Data Firehouse
- [x] Amazon SNS Filtering, Failure Management in Event Driven Architecture
- [x] Building an Event Driven Apllication 

### Friday 22-11-2024
- [x] Task - created an event and rules and tested the EventBridge rules on it.
- [x] Sources of events for EventBridge, Rule Targets
- [x] Best Practices for using Amazon EventBridge, Security and Reliability
- [x] AWS CICD (codeCommit, CodePipeline, CodeBuild, CodeDeploy, CodeStar, CodeArtifact, CodeGuru)

##

### Monday 25-11-2024
- [x] Analysing Lambda Function for Auto-tagging resources 

### TeusDay 26-11-2024
- [x] tested each an every services for tagging ( untagged dues to unavaiability of resources), error - in tagging codebuild(lacks permission to tag system tags)

### Wednesday 27-11-2024
- [x] Handled the error for codebuild and created a new logic for tagging it
- [x] creating new resources for the untagged services and re-tagging them to check if any error.
- [x] some resources which have not created , gone throught about it how to create and researched about it.

### Thursday 28-11-2024
- [x] Analysing Lambda Function for Auto-tagging for new resources 
- [x] Created a test event for the lambda function for tagging the new security group

### Friday 29-11-2024
- [x] Created the services and checked weather tagged - (CreateVolume, RunInstances, CreateSnapshot, CreateSecurityGroup, CreateNetworkAcl, CreateRouteTable, CreateVpc, CreateLoadBalancer, CreateTargetGroup
)
- [x] Analysed that there is no policy for Vault in glacier for tagging.
- [x] Created the services and checked weather tagged - (CreateBucket, CreateWebACL, CreateRestApi, CreateTable, CreateFunction, CreateWorkGroup, CreateKey
)
- [x] CreateQueue, CreateTransitGateway, CreateRepository

##

### Monday 02-12-2024
- [x] CreateDomain, CreateServer, CreateBackupPlan, CreateCluster
- [x] CreateClusterV2, CreateLogGroup, PutMetricAlarm, CreateProject
- [x] CreateFileSystem,CreateDeliveryStream, CreateNetworkInterface,CreateUser, CreateRole

### Teusday 03-12-2024
- [x] AllocateAddress, CreateVault, CreateService, CreateSubnet
- [x] CreateStateMachine, CreateUserPool, CreateIdentityPool, CreateImage(tested using event test as json)
 
 ### Wednesday 04-12-2024
 - [x] Updated the auto-tag code in workdrive and S3 through Amit.
 - [x] started with cdk(Cloud Development kit), installed the prerequisites.
 
 ### Thursday 05-12-2024
 - [x] Going through the CDK Concepts - Libraries, projects, apps, stacks, stages, constructs.
 - [x] Tried to create a CDK App for createing an EC2 instance

 ### Friday 06-12-2024
 - [x] Created a cdk for ec2 instance with security group and selecting the default VPC.(Error - SSM Pass)

 ##

 ### Monday 09-12-204
 - [x] rectified the error of my cdk and succesfully it create a cft stack.
 - [x] Updated the code - setting the security group rules as envt variables, from .env file
 - [x] Updated the code - setting the Ec2 instances in env variables, from .env file

 ### TeusDay 10-12-2024
 - [x] Created a cdk for ec2 instance with security group and selecting the default VPC in Python.
 - [x] Created a login and sign-up page using streamlit.
 - [x] Update the UI for the login page.
 - [x] Gone through AWS Cognito Concepts.

 ### Wednesday 11-12-2024
 - [x] Updated the login page using aws cognito(Authenticating the user using - initiate_auth()).
 - [x] Updated the signup page (creating the user in aws cognito using - sign_up() ).
 - [x] Created a confirmation page to confirm the email in cognito by sending a verifation code(using - confirm_sign_up()).

 ### Thursday 12-12-2024
 - [x] Created a ForgetPassword page for my login page using aws cognito (forgot_password, confirm_forgot_password)

 ##

 ### Monday 16-12-2024
 - [x] Created the logout for my streamlit apllication.
 - [x] Tried to bring the session data of the user on the home page and user profile
 - [x] Created the solutions page similar to Rapyder webpage

 ### TeusDay 17-12-2024
 - [x] initiated with the about page with a scroll down for the streamlit application.
 - [x] Tried with Django to do the s3 bucket operations with UI.
 - [x] Created a lambda function which gets triggered using API Gateway for getting the bucket details.

 ### Wednesday 18-12-2024
 - [x] Created a lambda function that gives the bucket details along with its object details in hierarchical order.
 - [x] Added the API gateway and tried to resolve CORS error.
 - [x] Created a contact form for the streamlit application

 ### Thursday 19-12-2024
 - [x] Tried to create a lambda function to return 10 S3 buckets name at every API Call.
 - [x] Created a lambda function which wil display the objects of the bucket and at every API call it will display the objects of that Folder.

 ### Friday 20-12-2024
 - [x] worked  with adding object to s3 bucket using lambda functions.
 - [x] Updated my streamlit app --(created a CCOE page and added somer services).
 - [x] streamlit app - displayed the S3 buckets using an API call.
 - [x] worked with login and logout page errors.


 ##

 ### Monday 23-12-2024
 - [x] Tried to update the streamlit apllication - added more option which should display the details of the bucket.
 - [x] Created a cdk for trigger a lambda function with an API Gateway.

 ### TeusDay 24-12-2024
 - [x] worked with the lambda function for the serach bar inside a bucket(to return the objects of that prefix and type of file or folder).
 - [x] worked with my cdk app for api gateway to lamda and tried to retify the bug (reduce the no of end points it created last time).

 ### Wednesday 25-12-2024
 - Holiday(Christmas)

 ### Thursday 26-12-2024
 - [x] worked with lambda function to use paginators for displaying 10 objects per page.
 - [x] worked on the same lambda fo the search query to return the objects of that preifix.

 ### Friday 27-12-2024
 - [x] Tried to clear the bugs(not returning the file type) of the lambda function for serach query in the bucket.
 - [x] worked with cdk and the api gatway will make a test-nvoke-stage by default which will not create any problem.. so we have to just ignore it.


 ##


 ### Monday 30-12-2024
 - [x] Updated the code for listBuckests to return the bucketCount with searchCount in the response.
 - [x] Updated the code for listBuckestObjects to return the ObjectCount with searchCount in the response.
 - [x] worked on the search function for the buckets(displaying the objects in the right hierarchy).
 
### Teusday 31-12-2024
- [x] Updated the code for listBucketObjects - debuged the searh operation and its returning response from till the end.
- [x] Updated the region for the code (when it selects for that bucket - it will go to that region and give the response).


### Wednesday 01-12-2024
- [x] New Year

### Thursday 02-12-2024
- [x] Debugged the code for the search function for the folders (not able to return reponse for larger buckets with more nested folders).
- [x] Started working for my Certification (EBS, EFS, AMI).

##

### Monday 06-01-2025
- Intern Leave

### TeusDay 07-01-2025
- [x] Continuation of Certification - ELB & ASG.
- [x] Initiated with GenAI -  LLM, Embeddings, Vector Database, Retrieval Augumented Generation, Langchain.

### Wednesday 08-01-2025
- [x] Initiated with Langchain Practices.
- [x] Gone through with AWS BedRock.
- [x] Created a APIGateway for RapyderAI.


### Thursday 09-01-2025
- [x] Created CDK for integrating HTTP-API Gateway with CORS integrating to the Lambda
