Analyze project

# Sonarqube

Login with admin/admin

1. Create new token
2. Select Java project
3. Maven builder
4. Copy maven generated commnad

Paste into terminal Sonarqube generated command, *Press enter* and wait for analysis results.

## Parameters Description

* *sonar:sonar*: maven stage to execute analysis
* *sonar.login*: Authentication Token
* *sonar.host.url*: Sonarqube server url

# Show results

Access to Sonarqube results dashboard https://[[HOST_SUBDOMAIN]]-9000-[[KATACODA_HOST]].environments.katacoda.com/dashboard/index/mygroup:myartifact
