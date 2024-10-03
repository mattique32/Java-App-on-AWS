# Java Web Applications on AWS

This repository contains the sample code for the Java web application and post confirmation sign up Lambda function as referenced in the blog post "Re-platform Java Based Web Applications on AWS". It also contains the cloud formation templates required to set up the AWS infrastructure, SQL script to create the supporting database and configuration files for the web server, Tomcat application server and Redisson cache. 

## Getting Started
* Build the sample-webapp maven project and place the WAR file in your S3 bucket
* Build the aws-signup-lambda project and place the JAR file in your S3 bucket
* Refer to the blog post for detailed steps

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

