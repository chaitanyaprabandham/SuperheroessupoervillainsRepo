# SuperheroessupoervillainsRepo

This repository will hold the Super Heroes Super Villains Covid 19 Project.

This Project is build on Java and Selenium and is Keyword driven. I have built this project in my personal computer and any path reference have to be changed on targer machine accordingly.

#Pre-requisite Depednacies :
This project is using the below plugins 
1.Java 8
2.Selenium Server 4.1.x
3.poi-bin-5.1.0 (Excel operations)
4.Chrome driver 
5.msedgedriver
6.javax.mail-1.5.0.jar (for test mail mailing functions)
7.log4j

#test
TestMain.java is the main test file which has to be run as Java application

#How to run project

As this project is key word driven, please update the UserName,Password,Browser in the Covid19_TCs_TD file location in the path below: 

covid19\src\com\ExternalSources\Covid19_TCs_TD.xlsx

Once the file is updated, run TestMain.java as a Java application.

#NOTE :

To save memory, I have ended the browser session multiple times and you would see browser session getting closed frequently. This is expected as per design.

#logging

I have added Log4J logging to this project, and each detail can be found in the console log


#Properties

all important properties can be found in covid19\src\com\Configurations\Browser_ExternalSources.properties file.

