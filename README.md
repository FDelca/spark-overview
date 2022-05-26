# spark-overview

This repository holds a basic guide to use spark.
- Spark version: 2.5.2
- Python version: 3.7
In order to fullfill this requirements a [docker image](https://hub.docker.com/r/jupyter/pyspark-notebook) was used. 

## Guide to install a Docker Image
1. Install `docker` and `docker-container` - [tutorial](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04-pt)
2. Pull [docker image](https://hub.docker.com/layers/pyspark-notebook/jupyter/pyspark-notebook/spark-2/images/sha256-ebc1a962b4fd9f489b0147c0dfb79c91f232b73337c1ac9bcee695c21e0d646c?context=explore) with this command: `docker pull jupyter/pyspark-notebook:spark-2`
3. And run it. Using this command: 
    - ```docker run -it --rm -p 8888:8888 -v "${PWD}":/home/jovyan/work jupyter/all-spark-notebook:spark-2```;
    - Or one can use the docker desktop app - following this [video tutorial](https://www.youtube.com/watch?v=DAdCrDVECwY)