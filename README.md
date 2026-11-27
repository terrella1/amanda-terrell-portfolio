# Amanda Terrell | Cloud Support and AWS Projects

**Live portfolio:** [View the portfolio](https://mandie-cloud-portfolio.s3.us-east-2.amazonaws.com/index.html)  
**Updated resume:** [Download the resume](Amanda_Terrell_Cloud_Support_Resume_Updated.docx)  
**LinkedIn:** [Amanda Terrell](https://linkedin.com/in/amanda-terrell-27122a37a)

I am a remote customer service advocate with 10+ years supporting healthcare operations and resolving account, data, and workflow issues. This portfolio documents my hands-on learning in AWS cloud hosting and serverless services.

## Projects

### Cloud Resume Challenge
A static portfolio hosted on Amazon S3 and delivered over HTTPS with Amazon CloudFront. I configured IAM access and used GitHub for source control, with a GitHub Pages copy for comparison.

**Troubleshooting example:** During deployment, I encountered an HTTPS warning and set up CloudFront for HTTPS delivery. This helped me understand how delivery configuration affects browser security.

**Tools:** Amazon S3, Amazon CloudFront, AWS IAM, HTML, CSS, GitHub Pages

### Serverless Visitor Counter
A visitor counter connected to the portfolio. An Amazon API Gateway HTTP API invokes a Python AWS Lambda function, which atomically updates the total in an on-demand Amazon DynamoDB table. AWS CloudFormation is used for infrastructure.

**Tools:** Amazon API Gateway, AWS Lambda, Amazon DynamoDB, Python, AWS CloudFormation

### AWS Cost Calculator
An interactive portfolio estimate for selected S3, CloudFront, API Gateway, Lambda, and DynamoDB usage assumptions. The page shows its assumptions and links to AWS pricing references. It is a learning estimate, not a bill prediction.

## Run locally

Clone this repository and open the portfolio page (index.html) in a browser. The visitor counter calls the deployed AWS API, so its display depends on that service being available.
