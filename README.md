# Eureka Demo

A multi project with multiple microservices.

Inspired from https://www.techtalksteve.com/blog/1-gradle-setup-for-microservices/
And https://www.baeldung.com/spring-cloud-netflix-eureka


## troubleshooting multi-module build

If you have some trouble with java versions, change it in Settings > Gradle JVM. Do it for all modules, not just the first one.

Also change in the project structure if the right java is used

## Using the Eureka server

Run the Eureka server using the Intellij configuration.

You can look at the dashboard on http://localhost:8761

## Warning: not really working; I have to figure out the spring versions to match spring cloud...

https://github.com/eugenp/tutorials/tree/master/spring-cloud-modules/spring-cloud-eureka
Here for the solution.