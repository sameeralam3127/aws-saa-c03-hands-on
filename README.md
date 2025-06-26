## AWS SAA-C03 Hands-On Project Roadmap (100 Projects)

### **1. Core AWS Services (15 Projects)**

_Focus: Compute, Networking, Storage, and Monitoring Basics_

1. Launch EC2 with user data script (Apache/NGINX)
2. Create an AMI and Auto Scaling Group
3. Use Elastic Load Balancer with ASG
4. Set up VPC with public/private subnets
5. Launch EC2 in private subnet with NAT Gateway
6. Configure Security Groups vs NACLs
7. Use CloudWatch to monitor EC2 instance metrics
8. Create EBS volumes and snapshots
9. Use EFS with multiple EC2 instances
10. Host a static website on S3
11. Configure S3 versioning and lifecycle rules
12. Enable S3 replication (cross-region)
13. Use CloudTrail to log API calls
14. Use AWS Config to track resource changes
15. Set up basic CloudWatch alarms and dashboards

---

### **2. Security, Identity, and Compliance (10 Projects)**

16. Create IAM users, groups, roles, and policies
17. Configure MFA for IAM users
18. Create a custom policy for S3 access
19. Use AWS Organizations with SCPs
20. Assume IAM Role across AWS accounts
21. Use KMS for S3 server-side encryption
22. Configure S3 bucket policy for public/private access
23. Use Cognito for federated identity login
24. Audit permissions using IAM Access Analyzer
25. Enable GuardDuty and review findings

---

### **3. High Availability & Fault Tolerance (10 Projects)**

26. Deploy a highly available 3-tier web app
27. Use Route 53 with failover routing
28. Launch EC2 with ASG across AZs
29. Set up multi-region S3 bucket replication
30. Implement CloudFront with origin failover
31. Create RDS Multi-AZ deployment
32. Launch Aurora with read replicas
33. Create Elastic Beanstalk with rolling updates
34. Use ALB with multiple target groups
35. Use Route 53 health checks and weighted routing

---

### **4. Serverless & Event-driven Architectures (10 Projects)**

36. Write a Lambda function to resize images in S3
37. Create API Gateway + Lambda + DynamoDB CRUD API
38. Use Step Functions to coordinate Lambdas
39. Use EventBridge to trigger events from S3 uploads
40. Use SNS to trigger Lambda
41. Integrate SQS queue with Lambda
42. Use DynamoDB Streams with Lambda
43. Use API Gateway with custom domain and throttling
44. Deploy Lambda with environment variables and IAM roles
45. Monitor Lambda with CloudWatch logs and metrics

---

### **5. Application Integration & Messaging (10 Projects)**

46. Create a decoupled architecture using SQS
47. Publish/Subscribe system with SNS and SQS
48. Use EventBridge rules to trigger notifications
49. Use Step Functions with error handling and retries
50. Integrate API Gateway with SQS
51. Schedule Lambda functions with EventBridge (cron)
52. Use S3 events to start a processing pipeline
53. Build a serverless email sender with SES
54. Configure Dead Letter Queue (DLQ) for Lambda
55. Use AWS AppConfig for feature flags

---

### **6. Databases (10 Projects)**

56. Launch RDS MySQL/PostgreSQL
57. Migrate database using DMS
58. Use DynamoDB for a key-value store
59. Build a leaderboard app with DynamoDB
60. Use global tables in DynamoDB
61. Add TTL and streams to DynamoDB
62. Query DynamoDB with secondary indexes
63. Launch Aurora Serverless v2
64. Set up a read replica in another region
65. Use ElastiCache for Redis for caching

---

### **7. Cost Optimization & Well-Architected (5 Projects)**

66. Set up a budget in AWS Budgets
67. Use Cost Explorer to analyze usage
68. Use Trusted Advisor for cost recommendations
69. Create lifecycle policies for snapshots/S3
70. Analyze usage of Reserved Instances vs On-Demand

---

### **8. Monitoring, Logging, and Automation (10 Projects)**

71. Create a custom CloudWatch metric
72. Use CloudWatch Logs with EC2 and Lambda
73. Create a CloudFormation template to deploy EC2 + VPC
74. Use Systems Manager to patch EC2 instances
75. Schedule EC2 stop/start with Lambda
76. Automate backup with Data Lifecycle Manager
77. Use AWS CLI and Boto3 to automate resource creation
78. Deploy app using CodePipeline + CodeBuild
79. Use AWS Backup for RDS + EFS
80. Deploy CloudWatch dashboards with multiple widgets

---

### **9. Real-World Scenarios & Mini Projects (20 Projects)**

81. Build a photo album app (S3, Lambda, API Gateway, DynamoDB)
82. Create a URL shortener (Lambda, DynamoDB, API Gateway)
83. Design multi-account architecture using AWS Organizations
84. Set up a hybrid cloud architecture (VPN)
85. Migrate on-prem app using Snowball
86. Use VPC peering and test cross-VPC communication
87. Set up centralized logging solution
88. Host WordPress on EC2 with RDS backend
89. Set up a CI/CD pipeline for Lambda functions
90. Design an architecture for disaster recovery
91. Build a web scraper and store data in S3/DynamoDB
92. Create a chatbot with Lex and Lambda
93. Deploy containers using ECS Fargate
94. Set up EKS cluster and deploy sample app
95. Deploy static website using Amplify
96. Implement zero-downtime deployments with Blue/Green
97. Create a multi-region read-heavy architecture
98. Create a serverless job queue system
99. Implement user authentication with Cognito + API Gateway
100.  Design a scalable e-commerce app architecture

---
