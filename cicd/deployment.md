# Steps to deploy this application on EC2 using docker and github actions

1. Create the dockerfile
2. Write the cicd pipeline
3. Create Dockerhub Account. Add docker hub username and password to github secrets
4. Create an EC2 instance - Use ubuntu image - install docker
5. Create a self hosted runner


## To create a self hosted runner 
Go to Github repo settings
- On `Code and automation` tab expand `Actions` and click on `Runners`
- Click on `new self hosted runner` button
- On `Runner image` select `Linux`
- On `Architecture` select `x64`
- Copy the `Download` and `Configure` code step by step and run on the EC2 instance