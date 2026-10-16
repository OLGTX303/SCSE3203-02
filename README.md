# SCSE3203-02

Maven web application for the SCSE3203-02 Internet Programming lab.

## Build

```powershell
cd helloworld101
mvn clean package
```

The generated WAR file is created in `helloworld101/target/` and is intentionally excluded from Git.

## Run on Tomcat

Deploy `helloworld101/target/helloworld101.war` to Tomcat 11 and open:

`http://localhost:8585/helloworld101/hello`

The required source submission archive is included at the repository root.
