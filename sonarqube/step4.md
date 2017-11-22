Analyze project

# Sonarqube

Login with admin/admin

1. Create new token
2. Select Java project
3. Maven builder
4. Copy maven generated commnad

Go to repository path `cd atomist-spring-boot`{{execute}}

Paste into terminal generated command, *Press enter* and wait for analysis results.

## Parameters Description

* *sonar:sonar*: maven stage to execute analysis
* *sonar.login*: Authentication Token
* *sonar.host.url*: Sonarqube server url
