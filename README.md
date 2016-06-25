# Contenu

Repo contenant la configuration docker pour monter un blog wordpress avec quelques conteneurs

nginx <-> wordpress <-> mysql

avec memcached et cadvisor

Inspiration : https://wooster.checkmy.ws/2015/10/wordpress-docker

avec quelques modifications dans la configuration mysql :

- passage à mariadb
- avec un build spécifique suite au pb de droits lié à OSX / docker-machine / boot2docker 
