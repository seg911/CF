Configure:

aws configure

Usage:

aws cloudformation deploy --template-file .\cloudform.yaml --stack-name web --parameter-overrides BucketName=nftbox.tk DomainName=nftbox.tk HostedZoneId=Z2FDTNDATAQYW2 AcmCertificateArn=arn:aws:acm:us-east-1:162399442561:certificate/7746d2a0-5e4b-4096-a92b-cf084885383d