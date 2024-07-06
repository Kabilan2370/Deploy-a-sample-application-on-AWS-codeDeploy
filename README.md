# Deploy-a-sample-application-on-AWS-codeDeploy
Hello Everyone........
Here,I explained and created ,How deploy a sample application on AWS codedeploy

1. From the begning we login into our aws console.Here,we created 2 IAM role.(code-deploy,s3-server-access)
   ![Alt text](sample_screeshots/1.png)

2. Then,create a IAM user(assign a CLI access) to push your code on AWS bucket.
   ![Alt text](sample_screeshots/2.png)

3. Lets,we create a EC2 instance, this machine is push a code from using this machine
   ![Alt text](sample_screenshots/5.png)

4. Login into the EC2 machine using ssh port ,when you create a EC2 machine ,don't forget to attach a security group even by mistake. 

   ![Alt text](sample_screenshots/7.png)

5. To access a aws config ,install this credentials
    snap install aws-cli

6. Then ,Launch another EC2 machine for the deploy a sample application
   ![Alt text](sample_screenshots/8.png)

   Noticed here I,attached a IAM role which I created.This machine is know as deployment machine.
   [Alt text]([sample_screenshots/8.png](https://docs.aws.amazon.com/codedeploy/latest/userguide/codedeploy-agent-operations-install-ubuntu.html))
   
   
