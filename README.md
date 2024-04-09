<a href="https://gitlab.com/mudiatech/norway/-/pipelines" target="_blank"><img alt="pipeline status" src="https://gitlab.com/mudiatech/norway/badges/develop/pipeline.svg" /></a> 
<a href="https://gitlab.com/mudiatech/norway/-/jobs" target="_blank"><img alt="coverage report" src="https://gitlab.com/mudiatech/norway/badges/develop/coverage.svg" /></a> 

# Norway

Additional validator annotations for [Hibernate Validator](https://hibernate.org/validator/)


#### How to Use
1. Add GitLab package registry as maven repository

```xml
<repositories>
    <repository>
        <id>mudiatech</id>
        <url>https://gitlab.com/api/v4/groups/64413151/-/packages/maven</url>
    </repository>
</repositories>
```

2. Add this project as maven dependency

```xml
<dependency>
    <groupId>com.mudiatech</groupId>
    <artifactId>norway</artifactId>
    <version>0.2.0-SNAPSHOT</version>
</dependency>
```
