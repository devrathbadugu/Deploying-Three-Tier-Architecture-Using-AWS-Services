# Deploying-Three-Tier-Architecture-Using-AWS-Services
This 3-tier AWS VPC setup has web, app, and database layers. Traffic flows via Route 53, CloudFront, and an external ALB to EC2 web servers. An internal ALB routes requests to app servers, which interact with an Aurora MySQL DB. CloudWatch monitors, with S3 for logs.
