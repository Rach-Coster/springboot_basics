# springboot_basics
Based on the Springboot tutorial listed here: https://spring.io/guides/gs/spring-boot/#scratch


# Issues found 
1. The current JDK version (9.0.1) is incompatible with Spring, Groovy and Gradle which can result in warnings. Spring run will not run groovy files at all with this version.
2. JAVA_HOME does not work in Bash for Windows properly (like most things in Bash for Windows). The links that were created by in the enviroment variables were not accepted by bash but were accepted by the windows cmd line. 
3. Getting anything to install from the command line was an issue. I ended up just downloading the binary files and putting them in their designated myself. I also had to link them to PATH in the enviroment variables. 
4. I had to install Curl and Open SSL light to be able to use and display the results of curl requests on the command line. 


# Comments and Suggestions
- Using Maven would had made troubleshooting a lot easier and cleaner to write dependencies in. 
- I should really buy a Mac with my first paycheck..
