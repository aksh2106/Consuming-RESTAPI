# A mini project on consuming OpenWeatherMap's daily weather forecast API

A simple JAX-RS Client usage example. Fetches weather data from a openweathermap.org API and displays that on a simple UI.

To run the example, get a free API key from http://openweathermap.org/api and put it to place it at location: src/main/resources/META-INF/apache-deltaspike.properties

Use a JAX-RS 2.0 compatible server, Tomcat or any other, to deploy the application. Wildfly plugin is included in the pom.xml, so an easy method is just to execute:

mvn wildfly:run
