## Small docker project using compose ##

# install docker io
sudo apt-get install docker.io
 
 # to start docker service
 sudo service docker start
 
 # check system status
 systemctl status docker
 
 # to pull the image of centos
 sudo docker pull centos
 
 # run the image
 sudo docker run -it centos
 
 #### Docker compose ####
 Docker Compose is a tool that was developed to help define and share multi-container applications
 
  # install python-pip
  sudo apt-get install python-pip
  
 # install docker compose
 sudo pip install docker-compose
 
 # make dir #
 mkdir nginx
 
 # inside nginx & open docker compose file in vi editor #
 cd nginx
 vi docker-compose.yml
 
 # run docker compose file #
 docker-compose -f docker-compose.yml up -d
 
 # to see doc images#
docker images 
