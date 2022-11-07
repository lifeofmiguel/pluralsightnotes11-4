# pluralsightnotes11-4

Spring Framework: Spring Data JPA 5 with Hibernate

@Service tier
Annotated @Service
Describe verbs/actions of system
business logic belongs here
ensures business object state
transactional

@Repository 
Nouns of system (Data) focused on persisting and 
interacting with the database CRUD functions
OneToOne mapping with an object

@Entity goes before your class, needs primary key,
add @Id to top of your class also @GeneratedValue 
add variable private Long id; then create getter and
setter for Long id

Database Creation
spring.jba.generate-adl=true
spring.jba.hibernate.ddl-auto=create
by adding these 2 lines at end of application.properties
hibernate will create database and tables upon startup

@NamedQueries 
Stored in domain objects not required but focuses on 
domain named parameters

Springboot 2 The Big Picture

Implementation of Tomcat 2 allows basic app creation using PSVM
