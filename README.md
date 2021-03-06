# Swagger generated server

## Overview
This server was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.  By using the [OpenAPI-Spec](https://github.com/OAI/OpenAPI-Specification) from a remote server, you can easily generate a server stub.  This is an example of building a node.js server.

This example uses the [expressjs](http://expressjs.com/) framework.  To see how to make this your own, look here:

[README](https://github.com/swagger-api/swagger-codegen/blob/master/README.md)

### Running the server
To run the server, follow these simple steps:

```
npm install
node .
```

To view the Swagger UI interface:

```
open http://localhost:8080/docs
```

This project leverages the mega-awesome [swagger-tools](https://github.com/apigee-127/swagger-tools) middleware which does most all the work.

## Additional Tasks

Run all unit tests:

```
grunt test
```

Run code coverage:

```
istanbul cover node_modules/.bin/_mocha 
```

Set up watch for jshint and testing:

```
grunt watch
```