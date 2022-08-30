# Running the test <br />

Pre reqs: Install Java(jdk1.8) and  Apache Maven 3.8.6 then add bin directories to path variable<br />

In the file /applicationUnderTest.properties provide valid application property values for below properties. <br />
baseURL=<br />
orderendpoint=<br />
userrname=<br />
password=<br />

Download the zip file and extract to your local machine (windows). <br />
got to pom.xml file path in command promt <br />

execute command  :   mvn clean verify <br />
you can find serinity test report at \target\site\serenity\index.html location


