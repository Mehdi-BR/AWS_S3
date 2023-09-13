# Utilizing AWS's S3 bucket website and Terraform to deploy a portfolio:

In this project I learned how to utilize S3 bucket not only to store files but deploy a full fledged website,

The trickies part about this project is turning the bucket public so its accessible to everyone se we utilized (the official documentation)[https://developer.hashicorp.com/terraform/docs]

but most importantly :
- (s3 bucket website)[https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket_website_configuration]
- (s3 bucket acl)[https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket_acl]
- (s3 bucket object)[https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_object]

finally after applying our infrastructure we can go to bucket properties to get the link wher we can access the portfolio.

## Some screenshots:

![screnshot1!](/screenshots/Screenshot1.png "Screenshot1.png")

![screnshot2!](/screenshots/Screenshot2.png "Screenshot2.png")


![screnshot3!](/screenshots/Screenshot3.png "Screenshot3.png")