# TestMakerlab

Manually uploading and deploying code to update applications is a thing of the past. Using AWS tools like CodePipeline, CodeBuild, & S3 students will build a system that allows them to write and push code that triggers seamless and automatic deployments. Students will also setup an email notification that is sent to developers if a status change is made in the build process using , CloudWatch & SNS. Let the free times roll with Continuous Deployments.

## Development server

Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `npm run build -prod` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## What is covered?
- Setting up Github Repository
-- Create a public Github repository 
-- Clone provided code
-- Push provided code to new repository

- Setting up a CodePipeline
-- Configure a new CodePipeline with CodeBuild

- Setting up a CodeBuild
-- Configuring a new CodeBuild

- Setting up S3
-- Setting up S3 bucket for static hosting
-- Attach policy to IAM role (S3AdminAccess)

- View live Application

- Setting up CloudWatch event and SNS Topic
-- Create and subscribe to an SNS topic
-- Configure CloudWatch event to trigger on status changes in CodeBuild
-- See emails sent to subscribers to SNS topic

## Authors
* [Brock Tubre](http://brocktubre.com) - [Github](https://github.com/brocktubre)
