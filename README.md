# dockerized_solr
Docker configuration for running solr in a container

# solr 7.5.0
Place the solr cores folders in this folder and run `docker-compose up` in this folder to start solr.

You can edit the docker-compose file to use different port mappings.

`solr.xml` was taken from the cores folder of a Solr installation.

The environment variables in the docker-compose file were taken from `solr.in.sh` found in the `bin` folder of a Solr installation.

Note: Make sure to update the certificate passowrds in the `docker-compose` environment variables.