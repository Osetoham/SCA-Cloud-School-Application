# SCA Cloud Application School Exercise

This readme very clearly describes the test process and it's output, it also shows the instructions and documentaion used for the deployment in this excercise.

**Creating the Dockerfile that displays a webpage, each layers are inputted**

<img alt ='dockerfile-layers' src='img/dockerfile-layers.PNG'>

**Building the docker image, this command is run**

*docker build -t sca-cloud-exercise*
<img alt ='docker-image' src='img/dockerimage.png'>

*docker run -p 3000:80 sca-cloud-exercise*

<img alt ='docker-run' src='img/run.PNG'>

<img alt ='web-page' src='img/web.PNG'>

**The docker image is tagged, this command is run**

*docker tag sca-cloud-excercise mercyose/sca-cloud-excercise*

**The docker image is pushed to docker hub, this command is run**

*docker push mercyose/sca-cloud-excercise*
<img alt ='docker-push' src='img/dockerpush.PNG'>

