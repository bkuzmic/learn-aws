 # AWS Cloud Developer Associate
 
Training materials can be split into two parts:

* Free materials containing AWS whitepapers and FAQ

  * [Exam readiness](https://www.aws.training/Details/Curriculum?id=19185)
  
  STUDY TIP: Focus on the following whitepapers.
  
  * [AWS Well-Architected Framework](https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf) 
  * [Practicing Continuous Integration and Continuous Delivery on AWS Accelerating Software Delivery with DevOps](https://d1.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf) 
  * [Microservices on AWS](https://d1.awsstatic.com/whitepapers/microservices-on-aws.pdf) 
  * [Serverless Architectures with AWS Lambda](https://d1.awsstatic.com/whitepapers/serverless-architectures-with-aws-lambda.pdf) 
  * [Optimizing Enterprise Economics with Serverless Architectures](https://d1.awsstatic.com/whitepapers/optimizing-enterprise-economics-serverless-architectures.pdf) 
  * [Running Containerized Microservices on AWS](https://d1.awsstatic.com/whitepapers/DevOps/running-containerized-microservices-on-aws.pdf) 
  * [Blue/Green Deployments on AWS](https://d1.awsstatic.com/whitepapers/AWS_Blue_Green_Deployments.pdf)
      
  STUDY TIP: Focus on the following FAQs.
  
  * [Amazon Simple Queue Service](https://aws.amazon.com/sqs/faqs/)
  * [Amazon DynamoDB](https://aws.amazon.com/dynamodb/faqs/)
  * [Amazon ElastiCache](https://aws.amazon.com/elasticache/faqs/)
  * [Amazon Kinesis](https://aws.amazon.com/kinesis/data-streams/faqs/)
  * [AWS Lambda](https://aws.amazon.com/lambda/faqs/)
  * [Amazon API Gateway](https://aws.amazon.com/api-gateway/faqs/) 
  * [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/faqs/) 
  * [AWS Identity and Access Management](https://aws.amazon.com/iam/faqs/) 
  * [AWS Key Management Service](https://aws.amazon.com/kms/faqs/)
  
  More materials:
  * [Exam guide](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf)
  * [Sample questions](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Sample-Questions.pdf)

* Paid materials from Udemy:
  
  [Ultimate AWS Certified Developer Associate 2020 - NEW!](https://www.udemy.com/course/aws-certified-developer-associate-dva-c01/)

## Notes

Important notes based on Udemy course above.

**NOTE**
This is still work in progress.

| Section | Notes |
| ------- | ----- |
| Section 3 AWS Fundamentals: IAM + EC2 | - Multiple regions with multiple availability zones (min 2, max 6) <br> - Creating IAM account: never use root + protect root account using MFA (multi factor authentication) - applicable for Cloud Practitioner certification <br> - EC2 - virtual machine, setup security groups (firewall for inbound and outbound traffic), SSH access using key <br> - EC2 user data - setup scripts on boot time <br> - AMI, image for EC2 instance, can be custom and it is specific for AWS Region |
| Section 4: AWS Fundamentals: ELB + ASG | - Horizontal / Vertical scaling |