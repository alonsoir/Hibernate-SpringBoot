**[How To Configure BoneCP Via DataSourceBuilder](https://github.com/AnghelLeonard/Hibernate-SpringBoot/tree/master/HibernateSpringBootDataSourceBuilderBoneCPKickoff)**

**Description:** This is a kickoff application that set up BoneCP via `DataSourceBuilder`. The `jdbcUrl` is set up for a MySQL database. For testing purpose the application uses an ExecutorServicefor simulating concurrent users. 

**Key points:**\
     - in pom.xml, add the `spring-boot-configuration-processor` dependency\
     - in pom.xml add the BoneCP dependency\
     - in application.properties, configure BoneCP via a custom prefix, e.g., `app.datasource.*`\
     - write a `@Bean` that returns the `DataSource`

**Output sample:**\
![](https://github.com/AnghelLeonard/Hibernate-SpringBoot/blob/master/HibernateSpringBootDataSourceBuilderBoneCPKickoff/sample.png)

<a href="https://leanpub.com/java-persistence-performance-illustrated-guide"><p align="center"><img src="https://github.com/AnghelLeonard/Hibernate-SpringBoot/blob/master/Java%20Persistence%20Performance%20Illustrated%20Guide.jpg" height="410" width="350"/></p></a>