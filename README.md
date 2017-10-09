# Little P's web albums

## S3 configuration

1. Create two buckets in S3
    * parristhomas.com
    * www.parristhomas.com
1. Put content in `parristhomas.com`
1. Configure `parristhomas.com` to be a static website in S3.
1. Configure `www.parristhomas.com` to be a static website that always redirects in S3.

## Route53 configuration

1. Create an `A` record for `parristhomas.com`, make it an alias to its corresponding bucket.
1. Create another `A` record for `www.parristhomas.com`, make it an alias to its corresponding bucket.