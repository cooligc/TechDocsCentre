Spring 4
========
[![N|Solid](https://assets.toptal.io/uploads/blog/category/logo/59/spring.png)](Spring)

- **@Configuration** -> This declares it as a Spring configuration class
- **@EnableWebMvc** -> This enables Spring's ability to receive and process web requests. Necessary for interceptors too.
- **@EnableTransactionManagement** ->  Reverting incomplete database modifications using transactions
                                  Some database modifications involve several SQL queries, for example, inserting an object with attributes spread across several tables. If one of the queries fails, we would want to undo any
							  previous ones that were successful
	1. Add @EnableTransactionManagement to the Spring configuration class
	2. Add a DataSourceTransactionManager bean to the Spring configuration
	3. Annotate the DAO class with @Transactional
							 
							 
- **@ComponentScan** -> This will scan the stereo type annotation
