webbank

[![Git](https://app.soluble.cloud/api/v1/public/badges/d078af8b-8859-43ae-8eda-f289f7903031.svg?orgId=560723739106)](https://app.soluble.cloud/repos/details/github.com/bhuvi11/webbank?orgId=560723739106)  
=======

This is a simple web banking application, designed to demonstrate a wide range of Java application vulnerabilities. It is based on a "Spring by Example" sample application. The functionality and implementation of the application are intentionally contrived, and it is of no use except as an aid to learning about Java security. It is used by the "Penetration testing Java applications for fun and profit" training course. For more details, see [http://www.javapentesting.com/](http://www.javapentesting.com/)

## Local machine instance
### To build:
```sh
mvn clean package
```
### To run with embedded jetty:
```sh
mvn jetty:run
```
## OpenShift instance
```sh
rhc app create jpen jbossews-2.0 --from-code https://github.com/pentestingforfunandprofit/webbank.git
```
If you are new to OpenShift, refer to the [Getting Started Overview](https://developers.openshift.com/en/getting-started-overview.html).
