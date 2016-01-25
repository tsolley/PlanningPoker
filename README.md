# PlanningPoker

I would suggest using the Spring Tool Suite as an IDE. STS has great Gradle support.
Plus I made the project a Spring Boot project but it is configured to run from a local Tomcat.

Setting Up Gradle Project

1. Install Gradle http://gradle.org/gradle-download/ -> Complete distribution

2. Unzip and place on your C drive.

3. Setup a System Environment Variable. (GRADLE_HOME)

4. Add that to your PATH or path. (%GRADLE_HOME%\bin)

5. Open CMD and run gradle --version. You should see something like below:

	Gradle 2.10

	Build time:   2015-12-21 21:15:04 UTC	
	Build number: none	
	Revision:     276bdcded730f53aa8c11b479986aafa58e124a6
	

	Groovy:       2.4.4	
	Ant:          Apache Ant(TM) version 1.9.3 compiled on December 23 2013
	JVM:          1.8.0_71 (Oracle Corporation 25.71-b15)
	OS:           Windows 7 6.1 amd64

6. After you have cloned the project, navigate to the root directory. (PlanningPoker)

7. Run the following commands in the console:
	- gradle cleanEclipse
	- gradle eclipse
	- gradle build

8. Then import the project in STS as a Gradle project.
