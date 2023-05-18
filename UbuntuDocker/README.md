# Docker build 


git clone https://github.com/jeyeon2ee/dockerTest  
cd dockerTest/ubuntuDocker  
docker build --rm -t jeyeon2ee/ut:v2 .  
docker images  


# Docker run

docker run -it --rm -v c:\\Users\\kitri\\df:/df --name ut jeyeon2ee/ut:v2  
