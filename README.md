<a href="https://gitlab.com/mudia/pro/norway/-/pipelines" target="_blank"><img alt="pipeline status" src="https://gitlab.com/mudia/pro/norway/badges/develop/pipeline.svg" /></a> 
<a href="https://gitlab.com/mudia/pro/norway/-/jobs" target="_blank"><img alt="coverage report" src="https://gitlab.com/mudia/pro/norway/badges/develop/coverage.svg" /></a> 

# Norway

Additional validator annotations for [Hibernate Validator](https://hibernate.org/validator/)


#### How to Use
1. Add GitLab package registry as maven repository

```xml
<repositories>
    <repository>
        <id>mudia</id>
        <url>https://gitlab.com/api/v4/groups/64413151/-/packages/maven</url>
    </repository>
</repositories>
```

2. Add this project as maven dependency

```xml
<dependency>
    <groupId>com.gitlab.mudia.pro</groupId>
    <artifactId>norway</artifactId>
    <version>0.2.0-SNAPSHOT</version>
</dependency>
```
