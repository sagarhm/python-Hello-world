# Task -1 :Banao - Devops
1) Create a basic python or php web server that says :  "hello world"
2) Create a docker container for it.
3) host it on an EC2 or free azure server

# Flask-helloworld-Docker AWS-EC2
Sample project to build a flask hello-world application with docker and deploy it in AWS EC2 Machine 

Test it out with

```bash
$> docker build -t application:latest .
$> docker run -p 5000:5000 application:latest
```

Open http://35.175.149.193:5000/
