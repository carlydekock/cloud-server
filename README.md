# Lab 16: AWS Cloud Servers

Deploy a Node.js server to AWS EC2

## Author: Carly Dekock

### Link to GitHub [repository](https://github.com/carlydekock/cloud-server.git)

## Deployed Links
- GUI deployed server [here](http://cloudserver-env.eba-vfqp2yim.us-east-2.elasticbeanstalk.com/)
- CLI deployed server here

## Processes
- Ensure you have AWS account
- Ensure you have access keys

### GUI deployed server
- Ensure repo has server setup but has no database
- PORT is set in .env file
- Zip all files together for application, except package-lock.json and node_modules folder
- In Elastic Beanstalk console - create new application
- Select create new application
- Give the application a name
- Select platform: Node.js
- Select upload your code, and upload the zipped file

