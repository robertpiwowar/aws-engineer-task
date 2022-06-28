## AWS Engineering Task

CloudFormation templates for the following AWS resources have been developed on AWS as basic preparation for further deployment:
1. VPC
2. Subnets

Additionally, simple template for website on S3 has been created. 

### Your task

1. Access the infrastructure automation code located in the repository: https://github.com/robertpiwowar/aws-engineer-task
2. Fork the repository to your github account
3. Fix any errors in the current code (there is 1 syntax and 1 logical error)
4. Amend the code so that the website will be available over public internet but only accessible from your public IP
5. Enable website access log and send them to S3 bucket named ${BucketName}-logs
6. Update VPC and/or Subnets templates to reference VPC in Subnets by VPC stack name and avoid entering VPC Id
7. Add tags to VPC and S3 buckets, key: "Owner", value: your github username
8. Improve code formatting consistency if required

Once all of the above tasks are done, open a pull request to merge your changes to the original repository. Please note that your pull request will be reviewed by the assessors but not merged.

### Notes

- It is assumed that you have an existing GitHub account, if you don’t, please create one for the purpose of completing the task
- Completing all of the tasks should not take more than 1 hour
- You are not required to provide a deployed solution, only the code will be assessed
