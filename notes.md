## Joins

A `foreign key` is a column on a table that references the primary key on another table. 

A way to link a record (or row) in one table to a record in another table. 

A foreign key is a column which pairs to another table's primary key showing the relationship between rows. 

A foreign key is a column or group of columns in a relational database table that provides a link between data in two tables. Its acts as a cross-reference between tables as it references the primary key of another table, thereby establishing a link between them. 

## Application Architecture

Opinion.
    For an API we normally have (at least) 3 layers:
    -Routing (this is teh `express` i stuff, the endpoints, the middleware) => routers, helpers, middleware
    -Data Access  (Knex + SQlite || Postgres code) => Whatever name you decide. The model of the data. 
    -Business Logic (this makes your application unique) => regular pure functions packed into a module you can export