# postgresql-cheatsheet
Cheat sheet of commonly used commands for PostgreSQL

psql is an interactive terminal that comes with PostgreSQL. With it you can enter and run SQL queries and get any results in the console. You can also create stored procedures, run complete SQL scripts, do database maintenance and much much more. For most PostgreSQL users, this is the only interface they need and use with PostgreSQL.

## List databases
`\l`

## Connect database
Let's connect to a database. We do that using the \c [for "c"onnect] meta-command.
e.g.
`\c testdb2`

You are now connected to database "testdb2".

## Quit the command terminal
Use `\q` and press `ENTER` to actually quit psql.
or `CTRL + D`

## To list tables in a database
Use `\d` and press `ENTER`

## Run Script
We can run a complete script in psql in two ways: \i  [for "i"nteractive?] or psql -f. First, let's create a simple script.
e.g. `\i ./myscript.sql`
