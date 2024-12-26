## Assignment 2.12: Function as a Service

Given a Lambda function that is triggered upon the creation of files in an S3 bucket, answer the following:

**Q1. What is the purpose of the execution role on the Lambda function?**
<br>- The execution role is an AWS Identity and Access Management (IAM) role that grants the function permission to access AWS services and resources.

**Q2. What is the purpose of the resource-based policy on the Lambda function?**
<br>- For other AWS services and accounts to receive permissions to invoke the Lambda function.

**<p>Q3. If the function is needed to upload a file into an S3 bucket, describe: (i.e no need for the actual policies)**

**<p>a. What is the needed update on the execution role?**
<br>- To allow Lambda to do a “PUT” action into the S3 bucket.

**b. What is the new resource-based policy that needs to be added? To which resource?**
<br>- The new resource-based policy needs to be added to the S3 bucket to allow S3 to invoke the Lambda function.

