# DockerTomat
Build Tomcat docker

docker start <container_id>

docker commit <container_id> unbuntu:latest

docker run -it --rm -p 8888:8080 unbuntu /bin/bash


/opt/tomcat/latest/bin# ./catalina.sh start
