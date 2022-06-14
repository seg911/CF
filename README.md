Configure:

aws configure

Usage:

aws cloudformation deploy --template-file .\test.yaml --stack-name web --parameter-overrides DomainName=domain.io BucketName= HostedZoneId= CertificateArn=