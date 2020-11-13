# graphql-java-example
Example to start off with GraphQL using java

# Steps to start the graphiQL server:

execute the below commands from the folder where pom.xml file is present.
* use ```mvn clean install``` to build and install dependencies
* use ```mvn jetty:run``` to run the graphiQL server
* access using the following endpoint http://localhost:8080/

## Example query
below is a sample query which can be used to run on graphiQL UI
```{
  allLinks{
    url,
    description
  }
}
