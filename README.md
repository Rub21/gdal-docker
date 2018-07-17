# GDAL + AWS + Mapbox

## Install

```
docker-compose build
```


## Access to the container

```

docker run --env-file sample.env -v $PWD:/home/geolambda/work -it rub21/gdal:latest /bin/bash

```