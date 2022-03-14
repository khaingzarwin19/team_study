# Creating bucket and upload file to s3(aws management console & aws cli)

## Creating bucket

### using aws console
1. Sign in to the aws.amazon.com/console
2. Type `s3` in search box and go to the page of s3 buckets list.
3. Click `create bucket` button.
4. Add Bucket name. The bucket name must:
  - Be unique across all of Amazon S3.
  - Be between 3 and 63 characters long.
  - Not contain uppercase characters.
  - Start with a lowercase letter or number.
After you create the bucket, you cannot change its name
5. Set aws region
6. Choose `Block all public access` for private used
   (Then other settings are set as your needs.)
7. Choose `Create bucket`

### using aws cli

```
$ aws s3api create-bucket --bucket {my-bucket-name} --region {region}

eg. aws s3api create-bucket --bucket my-bucket --region us-east-1

```

## uploading file

### using aws console
- TODO

### using aws cli
- TODO


Ref:

- https://docs.aws.amazon.com/AmazonS3/latest/userguide/creating-buckets-s3.html

- https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3api/create-bucket.html
