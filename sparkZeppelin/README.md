# Setup:

Assumes that docker is installed.  The container downloads Spark, so it builds a little slowly.  
Has a few placeholders for adding in localstack aws config later

## Build and run container:

cd sparkZeppelin && docker build -t sparkzepp . 

docker run --name sparky -p 127.0.0.1:8889:8889 -td sparkzepp

to stop:  docker stop sparky

## Run 

http://localhost:8889/#/notebook/2A94M5J1Z
http://localhost:8889/#/notebook/2C2AUG798
