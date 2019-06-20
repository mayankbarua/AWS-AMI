# CSYE 6225 - Summer 2019

## Team Information

| Name | NEU ID | Email Address |
| --- | --- | --- |
|Mayank Barua |001475817 |barua.m@husky.neu.edu |
|Ronak Parkhiya|001491072 |parkhiya.r@husky.neu.edu |
|Jay Chitalia |001449258 |chitalia.j@husky.neu.edu |

## Technology Stack
* Shell Script
 

## Build Instructions
* packer validate centos-ami.json
* packer build \
    -var 'aws_access_key=REDACTED' \
    -var 'aws_secret_key=REDACTED' \
    -var 'aws_region=us-east-1' \
    -var 'subnet_id=REDACTED' \
    centos-ami.json

## Deploy Instructions
* Go to aws console and launch instance under ec2 service

## Running Tests

## CI/CD


