#Seam Solder Bug (SOLDER-116)

Please refer to [JIRA issue SOLDER-116](https://issues.jboss.org/browse/SOLDER-116) for a complete description

##Reproduicing the bug

    mvn -Pweld-ee-embedded-1.1 clean test

if you go to MyBean class and comment the @Inject at the beginig of the class, the bug doesn't show.

