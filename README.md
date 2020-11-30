# Share infrastructure

This repo contains all shared infrastructure elements for the SayWhat! app that can be imported to the different services.

* Custom domain name for API Gateways
* IAM Role for API Gateways to write to CloudWatch logs
* S3 Bucket to upload code files

Remember to add new pieces to `.github/workflows/cd.yml` to get them deployed.