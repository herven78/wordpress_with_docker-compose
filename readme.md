

#Deploiement en production d'un site wordpress avec Docker-compose

###Nous avons besoin :

###_d'une base de données MySQL ;_

###_le système de fichiers WordPress_


Creer un document dockerwordpress a l'interieur creer un fichier docker-compose.yml 
1-copie coller le code a l'interieur du fichier docker-compose.yml

2-Allez dans le dossier dockerwordpress/ et executez la commande

```sh

docker-compose up -d

```

3- Pour avoir un volume resistant , il vous faudra creer un dossier avec le nom "db_data" dans dockerwordpress/


###explication

image qui permet de spécifier l'image source pour le conteneur ;

build qui permet de spécifier le Dockerfile source pour créer l'image du conteneur ;

volume qui permet de spécifier les points de montage entre le système hôte et les conteneurs ;

restart qui permet de définir le comportement du conteneur en cas d'arrêt du processus ;

environment qui permet de définir les variables d’environnement ;

depends_on qui permet de dire que le conteneur dépend d'un autre conteneur ;

ports qui permet de définir les ports disponibles entre la machine host et le conteneur.


###Quelques commandes utiles 



