# AWS Signed URL Plugin #

This plugin will enable a wordpress user to sign a URL to access private content behind an Amazon CloudFront distribution.
Create a key pair and configure the CloudFront distribution appropriately as well as in this plugin and then you can use
the shortcode [wp-sign] to denote a URL to be signed.  You can also wrap the URL with tags [wp-sign]my-url[/wp-sign].

Full details of the generation of the keypair and configuration of AWS can be found in the 
[AWS documentation](http://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/PrivateContent.html)

This plugin does not manage the process of getting Media Assets on to Amazon S3 or modify the Domain name for AWS based
media - nor will it work for streaming media such as HLS video as all of the subassets need also to be signed and not
just the manifest file.
