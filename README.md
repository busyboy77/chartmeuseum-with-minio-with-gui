# chartmeuseum-with-minio-with-gui
chartmeuseum-with-minio-with-gui



# create directory for certs

`mkdir certs`

# Generate Certificates using certgen

` certgen --host "localhost,minio"`

# change the ownership to 1001

`chown -R 1001:1001 certs`

# Start the project

`docker-compose up -d`
