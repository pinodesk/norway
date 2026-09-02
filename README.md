![GitHub Release](https://img.shields.io/github/v/release/pinodesk/norway)
![CI](https://github.com/pinodesk/norway/actions/workflows/ci.yml/badge.svg)
![codecov](https://codecov.io/gh/pinodesk/norway/branch/main/graph/badge.svg)
[![Quality gate status](https://sonarcloud.io/api/project_badges/measure?project=pinodesk_norway&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=pinodesk_norway)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=pinodesk_norway&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=pinodesk_norway)
![License](https://img.shields.io/github/license/pinodesk/norway)

# Norway

Additional validator annotations for [Hibernate Validator](https://hibernate.org/validator/)

## How to Use

1. Add GitHub Packages as a Maven repository in your `pom.xml`:

```xml
<repositories>
    <repository>
        <id>github</id>
        <url>https://maven.pkg.github.com/pinodesk/norway</url>
    </repository>
</repositories>
```

2. Add this project as a Maven dependency:

```xml
<dependency>
    <groupId>com.pinodesk</groupId>
    <artifactId>norway</artifactId>
    <version>0.2.0-SNAPSHOT</version>
</dependency>
```
