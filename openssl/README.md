## encrypt file ##
openssl aes-256-cbc -salt -in financial-records-fy-2011-12.dbx   -out financial-records-fy-2011-12.dbx.aes
## decrypt file ##
openssl aes-256-cbc -d -in financial-records-fy-2011-12.dbx.aes -out financial-records-fy-2011-12.dbx

## connect to gmail mail server for testing purpose ##
openssl s_client -connect smtp.gmail.com:995
openssl s_client -connect smtp.gmail.com:995 -CApath /etc/ssl 
