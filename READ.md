 Node.js CI/CD Project with Jenkins and AWS EC2

A basic Node.js app demonstrating continuous integration and deployment (CI/CD) using Jenkins and AWS EC2. Includes a declarative Jenkinsfile to automate building, testing, and deploying the app.


  Features
- Node.js + Express
- Jenkins pipeline for CI/CD
- Deployment on AWS EC2
- PM2 for process management

 CI/CD Pipeline Overview

THIS PROJECT IS A `Jenkinsfile` TO DEFINE A CI/CD PIPELINE THAT:

1. **Clones the GitHub repository**
2. **Installs dependencies** using `npm`
3. **Optionally runs tests**
4. **Deploys the app** using `pm2` on an AWS EC2 instance

The pipeline is fully automated and runs whenever code is pushed to the repository (when integrated with GitHub webhooks).

  SETUP
1. Clone this repo
2. Run `npm install`
3. Run `npm start` or `pm2 start index.js`

 TECHNOLOGIES USED 
- Node.js
- Jenkins
- AWS EC2
- PM2

    DevOps SKILLS DEMONSTRATED
 - Pipeline-as-Code using Jenkins
- Automated deployment on AWS EC2
- Process management with PM2
- Secure and production-ready Node.js setup
