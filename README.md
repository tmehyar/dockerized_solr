# dockerized_solr
Docker configuration for running solr in a container

# solr 8.2.0
Place the solr cores folders in this folder and run `docker-compose up` in this folder to start solr.

You can edit the docker-compose file to use different port mappings.

`solr.xml` was taken from the cores folder of a Solr installation.

The environment variables in the docker-compose file were taken from `solr.in.sh` found in the `bin` folder of a Solr installation.