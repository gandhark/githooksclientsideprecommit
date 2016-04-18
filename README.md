# githooksclientsideprecommit
 This will run sonar analysis in incremental mode with issue report plugin.
 To run this and function correctly, you have to install Sonar Issue report Plugin within SonarQube server.
 After Running this command it will generate HTML reports which will have all issues present in updated/new files.
Print Output of sonar analysis for debug purpose.

Pre-requisite for this:
1. SonarQube analysis in analysis mode with same sonar-project.properties file as that of developers system has to be present on sonarqube server.
2.Each developers should be configured with sonarqube runner,  whose  configurations should be same as that of sonarqube server's configurations.
