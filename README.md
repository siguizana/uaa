# MenaUAA

Cette application a été générée avec la version JHipster 5.8.2, Vous trouverez la documentation complète sur [https://www.jhipster.tech/documentation-archive/v5.8.2](https://www.jhipster.tech/documentation-archive/v5.8.2).

C'est une application de type "UAA" (User Account and Authentication (UAA) Server) faisant parti de l'architecture des microservices. Des détails ? Reférez-vous [Doing microservices with JHipster][]

L'application a été générée pour fonctionner avec le service de découverte et de configuration avec le Registry. Donc si vous lancez l'application sans avoir démarrez au préalable le registry, il ne va pas fonctionner.

Par défaut, le registry est accessible en local à [http://localhost:8761](http://localhost:8761). Mais si vous décidez d'utiliser Heroku, il faudra changer le lien vers le registry.

Pour plus de détails, je vous recommende de lire la documentation sur [Service Discovery and Configuration with the JHipster-Registry][].

## Développement

La commande suivante permet de lancer l'application en mode developpement:

    ./mvnw


## Production

Vous pouvez aussi, configurer l'application, de sorte à générer un executable pour l'exécution dans un environnement de production :

    ```
	./mvnw -Pprod clean package
	```

Pour vous rassurer que tout marche, lancer la commande suivant, étant dans le repertoire du projet:

    ```
	java -jar target/*.war
	```

## Quelques liens utilies

[jhipster homepage and latest documentation]: https://www.jhipster.tech
[jhipster 5.8.2 archive]: https://www.jhipster.tech/documentation-archive/v5.8.2
[doing microservices with jhipster]: https://www.jhipster.tech/documentation-archive/v5.8.2/microservices-architecture/

[Using UAA for Microservice Security]: https://www.jhipster.tech/documentation-archive/v5.8.2/using-uaa/[Using JHipster in development]: https://www.jhipster.tech/documentation-archive/v5.8.2/development/
[Service Discovery and Configuration with the JHipster-Registry]: https://www.jhipster.tech/documentation-archive/v5.8.2/microservices-architecture/#jhipster-registry
[Using Docker and Docker-Compose]: https://www.jhipster.tech/documentation-archive/v5.8.2/docker-compose
[Using JHipster in production]: https://www.jhipster.tech/documentation-archive/v5.8.2/production/
[Running tests page]: https://www.jhipster.tech/documentation-archive/v5.8.2/running-tests/
[Code quality page]: https://www.jhipster.tech/documentation-archive/v5.8.2/code-quality/
[Setting up Continuous Integration]: https://www.jhipster.tech/documentation-archive/v5.8.2/setting-up-ci/
