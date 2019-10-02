# Eclipse RAP E4 Maven Tycho Example
Working Maven Tycho build setup of example Eclipse RAP with E4 Workbench project. The output is a `.war` that can be deployed to a servlet container, e.g. *Apache Tomcat*. After deployment the app can be accessed on `http://localhost:8080/rapHelloWorld2/e4`.
*Currently works only for Windows target platform.*

## Running build
Just go to the root directory and run `mvn clean verify`. Results are output in the `releng/..product/target` folder.
