Registry Eureka Discovery
----------------------------
Dans cette partie on va créer l'annuaire Registry Service basé sur NetFlix Eureka Server pour la découverte des services de l'architecture.

Qu'est-ce qu'Eureka Service Discovery ?
------------------------------
Eureka Server est une application qui contient les informations sur toutes les applications de service client .
Chaque service Micro s'enregistrera sur le serveur Eureka et le serveur Eureka connaît toutes les applications clientes s'exécutant sur chaque port et adresse IP. 
Eureka Server est également connu sous le nom de Discovery Server

-------------------------------
Dependance exigée:
-Eureka Server :  Spring-cloud-netflix Eureka Server.

![image](https://user-images.githubusercontent.com/61996048/143938947-2ec2a022-a741-48e6-b49e-cef849447ee8.png)
