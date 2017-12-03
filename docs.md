# Useful commands and workaround during development

This is a document i made to gather some commands and tips that i get during development issues fixing.

1.to connect to a docker postgresql database image:
```docker exec -it <docker database image name> psql -U <databaseusername> -W <dbpassword> <dbname>
```

You could not provide password and dbname  if you connect as Root for linux system

2.To upload file and load inside a form with Html, Css and javascript, refer to this [MDN tutorial](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/file)

3.Postgres select all tables

use this command to list all tables in a postgresql database

```\dt *.*
```
to delete database column

```
$ mysql> | psql> ALTER TABLE <table_name> DROP column <COLUMN_NAME>;
```

