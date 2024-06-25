# kubernetes-Jenkins

In this project I implemented the following steps:
1. Installing a kubernetes cluster with 1 master and 2 workers, on AWS ec2 instances.
2. Throw Jenkins server, I created a CI pipeline that pulls a Dockerfile Iv'e created from Gitlab server( SCM ), and Build a Docker image
3. Pushing the Image to DockerHub
4. Reading a deployment.yml and insert the updated image into the deployment using environment variable
5. Apply and making the app available using ingress
