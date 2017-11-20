Configure your Sonarqube server

# Run Sonarqube

Use Docker image to run Sonarqube and expose ports

Execute on terminal `docker run -d --name sonarqube -p 9000:9000 -p 9092:9092 sonarqube:alpine`{{execute}}

## Access to Sonarqube

Access to sonarqube server after docker execution from tab or using this link:
* [Sonarqube dashboard](https://[[HOST_SUBDOMAIN]]-9000-[[KATACODA_HOST]].environments.katacoda.com/)
