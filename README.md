# Lab 16: AWS Cloud Servers

Deploy a Node.js server to AWS EC2

## Author: Carly Dekock

### Link to GitHub [repository](https://github.com/carlydekock/cloud-server.git)

## Deployed Links
- GUI deployed server [here](http://testcloudserver-env.eba-tpuz2ds7.us-west-2.elasticbeanstalk.com/)
- CLI deployed server [here](http://cloud-server-env.eba-zyxidcat.us-west-2.elasticbeanstalk.com/)

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

### CLI deploy
- Ensure repo has server setup but has no database
- PORT is set in .env file
- In the terminal, run ```eb init```
- Select all relevant prompts
- Run the command ```eb create <env-name>```
- Run the command ```eb deploy```

## Credits and Collaborators
- Worked at lab table with Jason D, Jason Q, Nick M, and Seid
- Help from Jacob on GUI deployed server
