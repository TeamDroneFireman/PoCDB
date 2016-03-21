# PoCBackend
Ce dépôt contient le PoC Database pour le projet FiremanDrone

##1. PoC 

###1.1 Introduction
Ce PoC contient un docker file pour créer un container mongodb.
- Infos de la VM
Port : 27017
User : admin
Base : mongo-db1

###1.2 Get started 
 
 Build the app
 ```
 docker pull mongo
 ```
 ###Start the app on port 27017
 ```
 docker run --name mongo-db1 -d mongo
 ```
 ###Access mongo shell
 ```
 docker exec -it mongo-db1 mongo admin
 ```
