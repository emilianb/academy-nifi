# Data ingest using Apache NiFi
An introductory hands-on class to learn basic concepts of data flow, which will allow you to collect and transport data from numerous sources including real-time events, data from external sources, structured and unstructured data.

Use Cases:
* ingest data from database
    - table dump
    - query dump 
    - incremental
    - change data chapture
* ingest data from external sources 
    - files
    - REST APIs
* ingest streaming data 
    - kafka
* small ETL 
    - route
    - entich 
    - validate
    - transform

## Requirements

* Java 1.8+
* Maven 3+
* Docker
* Docker-compose

## Start the local environment 

``` 
git clone git@github.com:eSolutionsGrup/academy-nifi.git

cd ./academy-nifi/

docker-compose up -d
```
