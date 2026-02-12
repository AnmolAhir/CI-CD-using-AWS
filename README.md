# CI/CD Pipeline using AWS

## Project Overview
This project demonstrates a Continuous Integration and Continuous Deployment (CI/CD) pipeline using AWS services. It showcases how to automate the deployment process, ensuring quick and reliable deployment of applications.

## Technologies Used
- **HTML** - 48.4% of the project files are dedicated to structuring the content of the application.
- **CSS** - 48.3% focuses on the styling and presentation aspects.
- **JavaScript** - 3.3% for adding interactivity to the application.

## CI/CD Pipeline Components
The following AWS services are utilized in the CI/CD pipeline:
- **AWS CodeCommit**: A source control service that hosts Git repositories. This project utilizes CodeCommit for version control.
- **AWS CodeBuild**: A fully managed build service that compiles source code, runs tests, and produces software packages. 
- **AWS CodeDeploy**: Automates the deployment of applications to Amazon EC2 instances, serverless Lambda functions, or even on-premises servers.
- **AWS CloudFormation**: Used for defining infrastructure as code and managing AWS resources.

## Deployment Steps
1. **Source Code Management**: The source code is pushed to AWS CodeCommit.
2. **Build Process**: AWS CodeBuild is triggered to build the application.
3. **Deployment**: Once the build is successful, AWS CodeDeploy initiates the deployment process.

## Conclusion
This CI/CD pipeline streamlines the deployment of applications, reduces manual interventions, and minimizes the likelihood of errors during deployment.