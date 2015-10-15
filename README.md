# Swagger Code Generator

[This repo was forked from swagger-api/swagger-codegen. Click here to see original docs!](https://github.com/swagger-api/swagger-codegen)

## Overview
This is the swagger codegen project, which allows generation of client libraries automatically from a Swagger-compliant server.  

Check out [Swagger-Spec](https://github.com/swagger-api/swagger-spec) for additional information about the Swagger project, including additional libraries with support for other languages and more. 

## Build and run using docker

```
git clone https://github.com/swagger-api/swagger-codegen

cd swagger-codegen

./run-in-docker.sh mvn package
```

## Command to generate client code

```
java -jar modules/swagger-codegen-cli/target/swagger-codegen-cli.jar generate -i path/to/swagger/json/service.json -l java -o path/to/output-dir -c config.json
```

## Templates location:
``
Templates are located in:
modules/swagger-codegen/src/main/resources/Java
```
