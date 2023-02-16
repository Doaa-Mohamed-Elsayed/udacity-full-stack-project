# Udagram : Hosting a Full-Stack Application

## Author: Doaa Mohamed Elsayed

### Dependencies

```
- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures and host Frontend.

- Elastic Beanstalk used for hosting the API
```

### Installation

AWS services needed for running the application:

1. In AWS, RDS database running Postgres. <bucketforprojectudacityfrontend>
2. In AWS, a s3 bucket for hosting the uploaded files. <udagram-api.us-east-1.elasticbeanstalk.com>
Bucket name	bucketforprojectudacityfrontend
AWS Region	us-east-1
Block all public access	No
3. Configure static website hosting
4. Upload udagram frontend
5. Need to create IAM user with AdministratorAccess
6. Create an Elastic Beanstalk for udagram backend
    . Export the ENV variables needed as in set_env.sh.


