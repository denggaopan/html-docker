# html-docker

a html website runing at docker.

## steps
### step 1

git clone https://github.com/denggaopan/html-docker.git

### step 2

cd comingsoon

### step 3

docker pull nginx

### step 4

docker build -t comingsoon .

### step 5

docker login

### step 6

docker tag comingsoon:latest denggaopan/comingsoon:latest

docker push denggaopan/comingsoon:latest

### step 7

docker run -d -p 50000:80 --name comingsoon_1 denggaopan/comingsoon:latest

### view in chrome

http://localhost:50000

