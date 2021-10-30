# AWS Signed URL Plugin #

This plugin will enable a wordpress user to sign a URL to access private content behind an Amazon CloudFront distribution.
A key pair has to be created to configure the CloudFront distribution appropriately as well as this plugin. 
Full details of the generation of the keypair and configuration of AWS can be found in the 
[AWS documentation](http://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/PrivateContent.html)

This plugin does not manage the process of getting Media Assets on to Amazon S3 or modify the Domain name for AWS based
media.
