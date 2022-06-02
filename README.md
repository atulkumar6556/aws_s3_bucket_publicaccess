# aws_s3_bucket_publicaccess
give your aws s3 bucket public access

















          {
        "Version": "2012-10-17",
        "Statement": [
            {
                "Sid": "AddPerm",
                "Effect": "Allow",
                "Principal": "*",
                "Action": "s3:GetObject",
                "Resource": "arn:aws:s3:::yourbucketname/*"
            }
        ]
    }
