# terraform-aws-s3-bucket

A simple Terraform module to create an AWS S3 bucket.

## Usage v1.1.5

```hcl
module "s3_bucket" {
  source      = "<YOUR_ORG>/s3-bucket-1/aws"
  bucket_name = "my-bucket-1"
}
``` 