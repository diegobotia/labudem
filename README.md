[![CI/CD Pipeline](https://github.com/diegobotia/labudem/actions/workflows/build.yml/badge.svg)](https://github.com/diegobotia/labudem/actions/workflows/build.yml)
[![Quality gate status](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_labudem&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=diegobotia_labudem)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_labudem&metric=coverage)](https://sonarcloud.io/summary/new_code?id=diegobotia_labudem)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_labudem&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=diegobotia_labudem)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_labudem&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=diegobotia_labudem)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_labudem&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=diegobotia_labudem)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_labudem&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=diegobotia_labudem)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_labudem&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=diegobotia_labudem)
[![Reliability issues](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_labudem&metric=software_quality_reliability_issues)](https://sonarcloud.io/summary/new_code?id=diegobotia_labudem)
[![Maintainability issues](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_labudem&metric=software_quality_maintainability_issues)](https://sonarcloud.io/summary/new_code?id=diegobotia_labudem)

# labudem

Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random Aircraft
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

```shell
$ mvnw spring-boot:run
```
to download the node dependencies

### How to test it

Execute:

```shell
$ mvnw clean install
```

### How to get coverage test

Execute:

```shell
$ mvwn -B package -DskipTests --file pom.xml
```


