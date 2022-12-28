# class-terraform-static-website
This Terraform snippet will create S3 bucket with required permission to deploy Static website.

## Step to follow
1. Clone Repo
2. Change bucket attribute under bucket resource block and also change respective bucket policy.


Once S3 bucket is created, upload two HTML pages from S3 console, index.html and error.html.

3. To access website, Go to S3 console --> Bucket you created --> Properties, scroll down to the bottom, you will see option Static website hosting
and corresponding URL to access Website.
