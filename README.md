# ec2-tags-env

**This script is written for my personal usage, and may not be suitable to use in a production environment.**

Import your AWS EC2 (instance and IAM) tags as Shell environment variables.

## Requirements

- jq package https://stedolan.github.io/jq/
- AWS CLI tool https://github.com/aws/aws-cli (probably already installed in your AMI)
- aws command for AWS CLI must be in your path
- IAM policy allowing you to use `ec2:DescribeTags`

## Usage

    . ./import-tags.sh
