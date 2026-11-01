# Sample project to integrate with AWS cognito together with AWS Cloudfront
https://ithelp.ithome.com.tw/articles/10386231

# CloudFront set up highlight
## Behaviour 
Disable the caching and change to Managed-CachingDisabled  
Need to forward cognito host to origin with Managed-AllViewerExceptHostHeader
