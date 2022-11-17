# awslambda-selenium-java

**--Install the serverless framework**
npm install serverless -g
--Use shell commands to clone the repository and change the working directory to the Java example

git clone git@github.com:blackboard/lambda-selenium.git
cd lambda-selenium/lambda-selenium-java/

**Packaging A New Function**
To package the jar and deploy it, run the following command inside the lambda-selenium-java directory
gradle clean unzipLibs shadowJar deploy
This will package all of the required dependencies and code within the jar file. The libraries that we included in the resources folder will also be included in this jar. Once the jar has been built, you can find it in the build/libs folder. This jar will then be deployed as a new lambda function using the serverless framework.

Now the function is ready to be invoked.


----to be edited----
