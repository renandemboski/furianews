> **`psql --host <host> --username <user> --dbname <database> --port <port>`**  
> Opens a connection to a PostgreSQL server using full connection parameters.

> **`psql -h <host> -U <user> -d <database> -p <port>`**  
> Shortened version of the same command used to connect to a PostgreSQL database.

> **`createdb -h <host> -U <user> -p <port> <database>`**  
> Creates a new database on the PostgreSQL server.

> **`dropdb -h <host> -U <user> -p <port> <database>`**  
> Deletes a database from the PostgreSQL server.

> **`psql -h <host> -U <user> -p <port> -c "<SQL>"`**  
> Executes a single SQL command without opening the interactive shell.

> **`pg_dump -h <host> -U <user> -p <port> <database> > backup.sql`**  
> Creates a full SQL backup of a PostgreSQL database.

> **`pg_restore -h <host> -U <user> -p <port> -d <database> backup.dump`**  
> Restores a database from a custom-format dump file.

> **`psql -h <host> -U <user> -p <port> -f file.sql`**  
> Runs all SQL commands stored inside `file.sql` against the database.

> **`psql postgresql://<user>:<password>@<host>:<port>/<database>`**  
> Connects using a full PostgreSQL connection URL.
