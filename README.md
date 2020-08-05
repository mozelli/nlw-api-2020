# package.json
On script *start* I'm using the *ts-node-dev* (*tsnd* is the abreviation) to run the application 

## Flags:

- **--transpile-only**: convert the code TypeScrit in JavaScript;
- **--ignore-watch node_modules**: don't convert the code in the folder *node_modules*;
- **--respawn**: keep watching alteration in the code and update the application when a change is maked.

# Database
- Sqlite3;
- Knex;
- You can find the tables on the *migrations* files at `src/database/migrations/`.

# Routes

## Connections
- Route to list total connections;
- Route to create new connection

## Classes
- Route to create a new class;
- Route to list classes;
- Route to list classes sorted by subject, day and time;