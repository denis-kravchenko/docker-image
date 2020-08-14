# docker-image

*Create php file

*Create dockerfile

*Build docker image
- docker build -t myk8sapp.php . 

*Rename our tag(tag from DockerHub)
- docker tag myk8sapp:latest singed420/k8s:latest

*Log In into DockerHub
- docker login

*Pushing our image to DockerHum
- docker push singed420/k8s:latest

*Running our applicatin
- docker run -it -p 1234:80 singed420/k8s:latest
