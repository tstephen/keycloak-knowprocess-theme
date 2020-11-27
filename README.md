Keycloak KnowProcess Themes
===========================

This project provides a sidecar init container to deliver themes to the stock Keycloak container.

Build
-----

Simply:
```
mvn clean install
```

Deploy (to DockerHub)
---------------------

Requires credentials at command line or in ~/.m2/settings.xml
```
mvn deploy
```

Release History
---------------

- 1.1.0 - 27 Nov 20 - SRP theme (functional prototype)

- 1.0.0 - 13 Oct 20 - KnowProcess theme (functional prototype)



