# hello-restdocs-api-spec

## Generate OpenAPI specification

```
./gradlew clean openapi3
```

## Use Swagger Codegen

* Install Swagger Codegen

```
brew install swagger-codegen
```

* Generate Java code

```
swagger-codegen generate -i ~/IdeaProjects/hello-restdocs-api-spec/build/api-spec/openapi3.json -l java
```

Note that you should run the above command in a new directory as it will generate them in the current directory.
