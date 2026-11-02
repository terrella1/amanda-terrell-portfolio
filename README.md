# Amanda Terrell | Cloud Technology & Security

**Live portfolio:** [View the site](https://mandie-cloud-portfolio.s3.us-east-2.amazonaws.com/index.html)

A personal portfolio showcasing my transition into cloud technology through hands-on projects, AWS certification studies, and problem-solving.

## Projects

### Cloud Resume Challenge
A static portfolio hosted in Amazon S3 and delivered over HTTPS with Amazon CloudFront. The project gave me hands-on experience with cloud hosting, delivery, IAM permissions, and web security.

### Serverless Visitor Counter
A visitor counter connected to the portfolio. An Amazon API Gateway HTTP API invokes an AWS Lambda function written in Python, which updates the total in an on-demand Amazon DynamoDB table.

### AWS Cost Calculator — planned
A planned project to compare AWS service costs across practical scenarios and explore cost optimization choices.

## Built with

HTML · CSS · Amazon S3 · Amazon CloudFront · AWS IAM · Amazon API Gateway · AWS Lambda · Amazon DynamoDB · Python · GitHub Actions · GitHub Pages · AWS CloudFormation

## Run locally

Clone this repository and open `index.html` in a web browser. The visitor counter connects to the deployed AWS API, so its behavior depends on that service being available.
