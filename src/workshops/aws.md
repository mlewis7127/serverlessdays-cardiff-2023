# Serverless Web Application Workshop

In this workshop you'll deploy a simple web application that enables users to request unicorn rides from the Wild Rydes fleet. The application will present users with an HTML based user interface for indicating the location where they would like to be picked up and will interface on the backend with a RESTful web service to submit the request and dispatch a nearby unicorn. The application will also provide facilities for users to register with the service and log in before requesting rides.

The application architecture uses AWS Lambda, Amazon API Gateway, Amazon S3, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console. Amplify Console hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser via S3. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.

The content for the workshop is available online:

[https://github.com/aws-samples/aws-serverless-workshops/tree/master/WebApplication](https://github.com/aws-samples/aws-serverless-workshops/tree/master/WebApplication)

### Prerequisites

- Please bring your laptop for the hands-on workshop.
- AWS can provide AWS accounts for the workshop

### Speakers

- Michael Hume, Solutions Architect

Thank you!!!

**Location:** DevOps Group, Floor 22, Capital Tower, Greyfriars Rd, Cardiff CF10 3AG

**Date:** 12 February 2020

**Start Time:** 13:00

**Duration:** 4 hours

You must have a ServerlessDays ticket to book this workshop. You will be emailed a link to book the workshop after purchasing a ticket w/c 13th January 2020.