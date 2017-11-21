Analyze project

# Analysis

With copied command we are goign to add to next

Copy to terminal this command:

```shell
docker run -it --rm --name maven-environment -v $PWD/atomist-spring-boot:/usr/src -v $PWD/.sonar:/root/.sonar -w /usr/src maven:3.5.2-jdk-8 mvn verify
```

Add _sonar:sonar_ command from second step:

```shell
sonar:sonar -Dsonar.host.url=https://2886795322-9000-ollie01.environments.katacoda.com -Dsonar.login=48ae973564939a0139f606a53dafc5637c2db0b6
```

You should have a command like this:

```shell
docker run -it --rm --name maven-environment -v $PWD/atomist-spring-boot:/usr/src -v $PWD/.sonar:/root/.sonar -w /usr/src maven:3.5.2-jdk-8 mvn verify sonar:sonar -Dsonar.host.url=https://2886795322-9000-ollie01.environments.katacoda.com -Dsonar.login=48ae973564939a0139f606a53dafc5637c2db0b6
```

Press enter and wait for analysis results.
