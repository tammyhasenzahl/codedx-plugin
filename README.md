codedx-jenkins-plugin
=====================

A Code Dx plugin for Jenkins


To compile and run use the following commands in the root directory:

```
set MAVEN_OPTS=-Xdebug -Xrunjdwp:transport=dt_socket,server=y,address=8000,suspend=n
mvn hpi:run
```

To package up run:

```

mvn package

```

and then install using the Jenkins web interface.
