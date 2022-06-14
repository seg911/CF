Configure:

Install aws-cli.

$curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
$unzip awscliv2.zip
$sudo ./aws/install
$aws configure
$git clone https://github.com/seg911/CF.git
$cd CF

Requirements:

Route 53 - create hosted zone for domain.
AWS Certificate Manager - create domain cert.

Usage:

$aws cloudformation deploy --template-file .\cloudform.yaml --stack-name web --parameter-overrides BucketName=nftbox.tk DomainName=nftbox.tk HostedZoneId=Z2FDTNDATAQYW2 AcmCertificateArn=arn:aws:acm:us-east-1:162399442561:certificate/7746d2a0-5e4b-4096-a92b-cf084885383d