# DataCatalogueDeployment
This is a repository for anyone who whishes to use use DataCatalogue as an end user not as a developer.

# Deployment
In order to deploy DataCatalogue from the latest existing images in [Dockerhub](https://hub.docker.com/orgs/hbpmip/repositories) we can simply clone this repository (or download the docker-compose.yml file that it contains) and execute a docker-compose up in the same directory as the docker-compose.yml.

### Step 1: Clone repository
```shell
git clone https://github.com/aueb-wim/DataCatalogueDeployment.git
```

### Step 2: Change direcory to repository
```shell
cd DataCatalogueDeployment/
```

### Step 3: Run with docker
```shell
docker-compose up
```
