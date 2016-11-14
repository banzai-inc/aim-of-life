# The Financial Aim of Life

Our wonderful presentation on financial topics for the classroom.

## [TODO: Gotta fill in a description]

## Refresh SSL Cert

http://knightlab.northwestern.edu/2015/05/21/implementing-ssl-on-amazon-s3-static-websites/

```
aws iam upload-server-certificate --server-certificate-name teachbanzai.com --certificate-body file://./STAR_teachbanzai_com.crt --private-key file://./STAR_teachbanzai_com.key --certificate-chain file://./STAR_teachbanzai_com_bundle.pem --path /cloudfront/
```

NOTE: Do not leave off `file://`
