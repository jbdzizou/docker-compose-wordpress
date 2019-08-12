
Name
# docker-compose-wordpress

## Description
#### quick start
wordpress build with docker-compose

## Usage
#### container build
make a wordpress project name  
`$ mkdir { my-wordpress-dir-name }`

change directry  
`$ cd { my-wordpress-dir-name }`

container up  
`$ docker-compose up -d`  

login to localhost(your chrome or etc)  
http://localhost:8000

#### DB login
check the container status  
`$ docker-compose ps`  

login to db container  
`$ docker exec -it {my-container-name-db} /bin/bash`

check the container env  
`# env`

login to mysql  
`# mysql -u wordpress -p`  
Enter the password
