# Pre reqs to run the suite <br />

Pre reqs: Install Java and Maven.<br />

In the file /luxsoft/applicationUnderTest.properties provide  application properties details.<br />
baseURL=<br />
orderendpoint=<br />
userrname=<br />
password=<br />

Download the zip file and extract. <br />
got to pom.xml file path in command promt <br />

execute command  :   mvn clean verify <br />
you can fins serinity test report at \target\site\serenity\index.html location


