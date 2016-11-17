# Flask Zappa
Building serverless micro-services with Zappa and Flask

# Prerequists
```
$ pip install --upgrade pip
$ [sudo] pip install virtualenv
$ virtualenv env
$ source ../../env/bin/activate
$ pip install flask zappa
```

```
# Default profile
$ aws configure
$ aws configure set default.s3.signature_version s3v4

# Specific profile
$ aws configure set profile.bnannier.s3.signature_version s3v4

# Get user profile information
$ aws iam get-user

# Get user session key
$ aws sts get-session-token --duration-seconds 129600
```
