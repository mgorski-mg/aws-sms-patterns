# Amazon CloudFront Patterns

Sample app containing examples of sending SMSes using AWS services.

## Patterns

* sns-sms
    * Send SMS using AWS SNS

## Setup

### Prerequisites

* SAM cli

## Deployment

### Required variables to be set - deploy.ps1

* \[s3-bucket-name\] -> name of the Amazon S3 Bucket used to deploy AWS CloudFormation stacks.

### Deploy

```powershell
deploy.bat
```