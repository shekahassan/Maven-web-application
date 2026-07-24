# Maven Web Application

A Java web application built with Apache Maven and Apache Tomcat.

## Quick Start

**Build:**
```bash
mvn clean package
```

**Deploy to Tomcat:**
Copy `target/maven-web-app.war` to Tomcat webapps directory.

**Docker:**
```bash
docker build -t maven-web-app .
docker run -p 8080:8080 maven-web-app
```

## Tech Stack

- Java Web Application
- Maven Build System
- Apache Tomcat Server
- Docker & Kubernetes Support
- Jenkins CI/CD Pipeline

## Project Files

- `pom.xml` - Maven configuration
- `Dockerfile` - Docker image definition
- `k8s-deploy.yml` - Kubernetes deployment configuration
- `src/main/webapp/` - JSP web pages

## Access

Once deployed: http://localhost:8080/maven-web-app
