# Spring on google cloud

This application is a POC for improved CI/CD pipeline.    
The application will build docker images from the application based on specific maven profile.

## Requirements
- Maven 3.6 or newer
- Java 8
- Docker 

### Local development
Maven with default profile will run in dev mode.
 
With defaults:
`clean package com.google.cloud.tools:jib-maven-plugin:1.3.0:build -DskipTests`

With image in cmd:
`clean package com.google.cloud.tools:jib-maven-plugin:1.3.0:build -Dimage=nbdev/myimage:0.0.1 -DskipTests`



