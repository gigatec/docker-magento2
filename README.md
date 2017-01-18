# Docker image for Magento 2

[![](https://images.microbadger.com/badges/image/netzkollektivgmbh/docker-magento2.svg)](https://microbadger.com/images/netzkollektivgmbh/docker-magento2)

[![Docker build](http://dockeri.co/image/netzkollektivgmbh/docker-magento2)](https://hub.docker.com/r/netzkollektivgmbh/docker-magento2/)

This image is a development environment for Magento 2 projects. You may either set up a **new Magento 2** installation with the provided install script or use the image with your **existing Magento project**.

## Usage

### Install Magento 2

```
docker-compose up -d
docker exec -ti {containerId} install
```

## Use with existing Magento 2

```
docker-compose up -d
```
