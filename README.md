# jenkinscicd
This Jenkins Pipeline will perform the following tasks:  - Ensure JDK 17 is available - Clone the Spring Petclinic Sample Application - Run OWASP Dependency-Check to check for CVEs - Compile the code using Maven
Write a Jenkins Pipeline that will accomplish the following tasks

-          Ensure JDK 17 is available

-          Clone Spring Petclinic Sample Application or another sample project of your choice.
https://github.com/spring-petclinic/spring-framework-petclinic

-          Run OWASP Dependency-Check to check for CVEs

-          Dont try to fix any reported issues, just catch the error and mark the stage as unstable
https://owasp.org/www-project-dependency-check/

-          Use Maven or Gradle to complie the code

-          Use Docker or Buildah to build the container image

-          Push the container image to either Docker Hub or Quay.io - create your own account
