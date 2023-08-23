# Create-a-static-website-using-Amazon-s3-Amazon-Route-53-ACM-and-cloudfront.

1. **Create an S3 Bucket**:

   - Created a new S3 bucket and configured it for static website hosting.
   - Uploaded a static website file.(HTML) to this bucket.

2. **Configure ACM Certificate**:
   - Requested an SSL/TLS certificate using AWS ACM.
   - Followed the prompts to prove ownership of my domain.
   - Once approved, the certificate was issued.

3. **Configure Route 53**:
   - I got a registered domain through Route 53.
     
4. **Configure CloudFront Distribution **:
   - For improved performance, I used Amazon CloudFront, a content delivery network (CDN), in front of my S3 bucket.
   - Created a CloudFront distribution and configured it to use my S3 bucket as the origin.
   - I also associated the ACM certificate with it to enable HTTPS.
  
   - Created an Alias record in Route 53 that points to my CloudFront distribution. This record associates my 
     domain name with the CloudFront distribution.
     
   
Link to my website.

https://iamjossi.com/

Link to diagram describing this architecture.

https://lucid.app/lucidchart/c3b639bc-4d7b-4d07-be31-d3fc3ed2f74a/edit?viewport_loc=-11%2C440%2C1381%2C664%2C0_0&invitationId=inv_5258f233-ebdc-4bc4-87c8-78ef3681b9c1
