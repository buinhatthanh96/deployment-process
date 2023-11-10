## AWS RDS Postgres Integration

The integral database component supporting data storage and retrieval for the application server is AWS RDS Postgres. The PostgreSQL database resides at the following URI:

**Database URI:** `postgres://postgres:Fpt12345@database-1.ccapmjuzodej.us-east-1.rds.amazonaws.com:5432/postgres`

Establish a connection to the database using the provided URI to execute diverse database operations within the Udagram application.

## Seamless Deployment with AWS Elastic Beanstalk

For deployment and scalability of the application server, AWS Elastic Beanstalk is the chosen platform—a fully managed service streamlining web application deployment. This service automates resource provisioning, including EC2 instances and load balancers, facilitating the seamless operation of the application.

The Udagram Full-Stack application undergoes construction, archiving, and uploading to an S3 bucket. Elastic Beanstalk retrieves the application from the S3 bucket, deploying it to an endpoint. Access the deployed application via the following Elastic Beanstalk URL:

**EB URL:** `http://udagram-api-dev.eba-up8gzxup.us-east-1.elasticbeanstalk.com/`

Explore the Udagram application's features, including image uploading and viewing, by navigating to the provided EB URL.

## Hosting Udagram Frontend with AWS S3 Bucket

The frontend aspect of Udagram Full-Stack resides on AWS S3 Bucket. Bundled assets of the Angular application—HTML, CSS, and JavaScript files—are uploaded to the S3 bucket. Public read access is configured, enabling end users to interact with the frontend application.

**Bucket URL:** `http://udagram-deploy.s3-website-us-east-1.amazonaws.com/`

Visit the designated Bucket URL to access the Udagram frontend application, where you can seamlessly share and view images.

## Quick Start Guide

To initiate the setup and deployment process for the Udagram Full-Stack application, follow these steps:

1. Connect to the AWS RDS Postgres database using the provided URI and execute necessary database operations.
2. Utilize the Elastic Beanstalk URL to access the application and engage with the deployed backend API.
3. Navigate to the S3 Bucket URL to explore and utilize the features of the frontend application.
