## Welcome to Guiro (User-Guided Matrix Reordering)

You can access the source code here.

### List of Microservices

- Gateway: Connects Microservices; Central Login; Front-End
- Matrixordering: contains all the matrix reordering algorithms and R-bridge (based on docker: rocker/verse); REST Swagger
- Featureprojector: contains all the projection algorithms; REST Swagger
- Database: stores the data and caches results; MongoDB (docker: mongodb)
- FeatureStats: gives statistics about dataset
- Kafka, Zookeeper, MariaDB: Service functionality in the background; inter-service communication;

Our implementation is based on Jhipster <www.jhipster.io>. More info there.


### Running the microservices

TBD


