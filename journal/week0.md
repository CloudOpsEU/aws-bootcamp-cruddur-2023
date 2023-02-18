# AWS Security and Optimization Tasks.

In order to ensure the security and optimization of our AWS environment, we have performed the following tasks:

- Destroyed our root account credentials: To ensure the highest level of security, we have deleted our root account credentials and have set up individual IAM users with specific permissions.

- Set up MFA and IAM roles: We have also set up multi-factor authentication (MFA) for all users, and have assigned specific IAM roles to each user to ensure that they only have access to the resources they need.

- Set up billing alarm and AWS budget: We have set up a billing alarm and an AWS budget to ensure that we are aware of any unexpected costs or usage spikes, and can take action to optimize our resources and costs.

- Used EventBridge to hookup Health Dashboard to SNS: We have set up an EventBridge rule to connect our AWS Health Dashboard to SNS, so that we receive notifications when there is a service health issue.

- Reviewed all questions of each pillar in the Well-Architected Tool: We have reviewed all the questions in each of the five pillars of the Well-Architected Tool, including Operational Excellence, Security, Reliability, Performance Efficiency, and Cost Optimization. This helps us ensure that our architecture meets best practices and is optimized for our use case.

- Created a CI/CD pipeline architectural diagram in Lucid Charts: We have created an architectural diagram of our CI/CD pipeline in Lucid Charts, to provide a clear visual representation of our pipeline and help us identify any areas for improvement.![Cruddur_Logical_Diagram](https://user-images.githubusercontent.com/93763783/219880180-08a03c93-9d70-446a-9e5b-a9d8b6247b70.png)

A napkin architecture was also done to give rough sketch of what we want to achieve.
[crudder_napkin_architecture.pdf](https://github.com/CloudOpsEU/aws-bootcamp-cruddur-2023/files/10774810/crudder_napkin_architecture.pdf)

- Researched technical and service limits of specific services: We have researched the technical and service limits of specific AWS services, such as EC2 and S3, to understand how they could impact our technical path for technical flexibility.

- Opened a support ticket and requested a service limit: We have opened a support ticket and requested a service limit increase for a specific AWS service, to ensure that we have enough resources to meet our needs.

By performing these tasks, we are confident that our AWS environment is secure, optimized, and well-architected to meet our needs.
