# swagger-combine

I have used Maven build for this application. You have to pass the Swagger.jsons via arguments.

In the POM.xml, add below dependencies:
<!-- https://mvnrepository.com/artifact/commons-io/commons-io -->
<dependency>
    <groupId>commons-io</groupId>
    <artifactId>commons-io</artifactId>
    <version>2.6</version>
</dependency>
<dependency>
			<groupId>io.swagger</groupId>
			<artifactId>swagger-parser</artifactId>
			<version>2.0.0-rc1</version>
</dependency>
<dependency>
			<groupId>io.swagger</groupId>
			<artifactId>swagger-core</artifactId>
			<version>2.0.0-rc2</version>
		</dependency>
    
    
