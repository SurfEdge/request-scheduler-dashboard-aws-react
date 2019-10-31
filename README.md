# Under Development!!!

# ⏰ Request Scheduler Dashboard  🚀
A dashboard to manage scheduled requests using AWS services and React.

💡Idea is to build a self manageable request scheduller and use the services from AWS to provide seamless experience. 

## Expected Features 🚀
- Per minute refresh (AWS Scheduled Lambda)
- Supports requests based on a specific time on daily basis
- Supports requests based on a week day with time
- Timezone support
- Log all the requests based on the app
- Log of the cron time and time elapsed for an instance

## Project Structure
This project will have two parts,
1. Dashboard - React Web Application to manage the requests and to view logs
2. Serverless project - AWS Lamdbda Function to handle requests minute by minute

## Expected Project Technologies/Frameworks/Services
- React
- Amplify Library
- Serverless framework
- AWS AppSync - GraqhQL
- AWS DynamoDB
- AWS Cognito
- AWS CloudWatch

To be updated later!

## Dependencies
- Scheduled lambda project boilerplate - https://github.com/SurfEdge/serverless-scheduled-boilerplate
More information https://docs.aws.amazon.com/lambda/latest/dg/tutorial-scheduled-events-schedule-expressions.html

- Material React Template - https://github.com/creativetimofficial/material-dashboard-react

💡Inspired by the previous project on PHP https://github.com/SurfEdge/ideamart-isyd-cron-job
