# AdventureWorks for Postgres

This is based off the work done by [lorint](https://github.com/lorint/AdventureWorks-for-Postgres). We've already done the work to convert the csv's to be compatible with postgres. If you would like the original files, head over to [Adventure Works 2014 OLTP](https://msftdbprodsamples.codeplex.com/downloads/get/880662) download page. The download includes a script for loading the data into MSSQL Server.

## Acknowledgement

[NorfolkDataSci repo](NorfolkDataSci/adventure-works-postgres) has done all the heavy lifting of translating the scripts.

## Getting started

First, make sure you have [docker](https://docs.docker.com/install/) and [docker-compose](https://docs.docker.com/compose/install/) installed postgres installed. 

### Run the script in a docker container

```bash
> docker-compose up -d
```

### Access the database

Enter the container:
```bash
> docker exec -it postgres /bin/bash
```
Use `psql` as you would if installed locally