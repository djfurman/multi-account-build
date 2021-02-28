# multi-account-build

AWS Practices and Templates for Building a Well-Managed Multi-Account Approach

## Resources

### CloudTrail

For an organization wide CloudTrail, build the log account, then execute the [central-log](templates/central-log.yml) CloudFormation template. Afterward, establish the organization log.

### Corporate Website

Most companies need a brochure page in order to operate. Since this is largely static content, hosting the site within an S3 bucket is both cost effective and allows a CloudFront element to provide global CDN. The [website-bucket](templates/website-bucket.yml) CloudFormation template creates this S3 origin.
