# Docker-image-html-helloworld


If you want to access this so Follows these steps:

step1: Clone the repository
cmd  : git clone https://github.com/A-Rehman01/Docker-image-html-helloworld.git

//if you want to pull image


step1: pull image form dockerhub
<br>
cmd  : <strong> docker image pull abdulrehman001/helloworld  </strong>

step2: Build  image
<br>
cmd  : <strong>  docker image build -t imagename  </strong>

step3: make container
<br>
cmd  : <strong> docker container run --name=containername -d -p 8030:80 imagename  </strong>

step4: run this address on your browser
cmd  : http://localhost:8030/
