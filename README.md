# FGH-workshop

## Example

### build a docker image
docker build -t demo .

### tag image 
docker tag demo:latest 1234567890.dkr.ecr.eu-west-1.amazonaws.com/demo:latest

### push image
docker push 1234567890.dkr.ecr.eu-west-1.amazonaws.com/demo:latest

### pull image
docker pull 1234567890.dkr.ecr.eu-west-1.amazonaws.com/demo:latest
