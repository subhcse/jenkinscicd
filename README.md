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

-      
Here are the prerequisites for setting up the Jenkins pipeline for the Spring Framework Petclinic application:
1. Java Development Kit (JDK) installed on your machine.
2. Apache Maven installed on your machine.
3. Docker installed on your machine.
4. A Docker Hub account.
5. A Jenkins server installed and configured.
6. The Spring Framework Petclinic application source code cloned to your local machine



To set up the Jenkins pipeline for the Spring Framework Petclinic application, follow these steps:
1. Create a new Jenkinsfile in the root directory of your project. Copy and paste the code from the above response into the Jenkinsfile.
2. In the Jenkins web UI, create a new pipeline job.
3. In the job configuration, select the "Pipeline" option under "Definition".
4. In the "Pipeline" section, select the "Jenkinsfile" option and enter the path to your Jenkinsfile.
5. Click the "Save" button.
6. Click the "Build Now" button to start the pipeline.
The pipeline will then run through the stages defined in the Jenkinsfile, building and testing the application, and deploying it to a Docker container.
