
# AWS S3 Bucket Management

This Bash script allows you to manage AWS S3 buckets. You can create a bucket, list the contents of a bucket, delete a bucket, upload files to a bucket, delete files from a bucket, and download files from a bucket.

## Prerequisites

- AWS CLI configured with proper credentials
- Bash shell

## Usage

1. Make sure you have the AWS CLI installed and properly configured with your AWS credentials.
2. Clone the repository:


git clone git@github.com:h93n/s3-aws-cli.git
cd your-repo

3. Run the script:


./s3_bucket_management.sh


4. Choose an action to perform by entering the corresponding number:

   1. Create S3 bucket
   2. List S3 bucket
   3. Delete S3 bucket
   4. Upload file
   5. Delete file
   6. Download file
   7. Quit

5. Follow the prompts and provide the necessary information for the chosen action.

## Functions

- `create_s3`: Creates a new S3 bucket.
- `list_s3`: Lists the objects in a specific S3 bucket.
- `delete_bucket`: Deletes a specific S3 bucket.
- `upload_file`: Uploads a file to a specific S3 bucket.
- `delete_file`: Deletes a file from a specific S3 bucket.
- `download_file`: Downloads a file from a specific S3 bucket.

