[![Build Status](https://travis-ci.org/blixit/jsonlikeql.svg)](https://travis-ci.org/blixit/jsonlikeql)

# jsonlikeql 
A language which let you write SQL queries with the Json like format. It has been inspired from GraphQL syntax. Its compiler is built with Galgas.

In fact, JsonLikeQL has been designed to reduce the writting of sql queries by using a high level language which looks like Json format. This query language is designed for a server-side use. That means that only a server-side program can parse a given query and execute it. 


## Features we're targeting !

JsonLikeQL should allow the developper to write the 4 main queries of a SQL Database Management System : Select, Insert, Update and Delete. For more about the specifications, please follow this link : [Wiki] (https://github.com/blixit/jsonlikeql/wiki)

In a select query, it is possible to use field Propagation. We introduced this concept to facilitate the write of joins or nested queries and then makes JQL queries easy to write. This behavior is possible thanks to the declaration of user (the developer) types to describe how database relations are related.

## How does it work ?

A text representing the JQL query is send to the server. The server submit this query to a parser. If no errors occur, the query is converted to a real SQL query. The server execute this query and return the result in a Json formatted string such as the output format matchs the input.

## More to come ... 

The Language is being written at the moment. The documentation will come along the development.
