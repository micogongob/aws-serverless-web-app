# JavaScript AWS Serverless Web App

This is based from [Pluralsight - Building a Serverless Web App with AWS Services](https://www.pluralsight.com/guides/front-end-javascript/building-a-serverless-web-app-on-aws-services) meant to be an exemplar project to showcase a serverless fullstack web app using:
- AWS Gateway + AWS Lambda running on NodeJS
- AWS DynamoDB NoSQL database
- [ReactJS frontend](https://github.com/eh3rrera/react-app-frontend) with S3 static site hosting

### setup
```bash
$ make .env deps
```

### deploy api
```bash
$ make deployApi
```

### deploy frontend to s3
```bash
$ make deployFrontend
```
