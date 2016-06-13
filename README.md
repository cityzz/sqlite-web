Fork from coleifer/sqlite-web

`sqlite-web` is a web-based SQLite database browser written in Python.

Project dependencies:

* [flask](http://flask.pocoo.org)
* [peewee](http://docs.peewee-orm.com)
* [pygments](http://pygments.org)

### Usage

```sh
$ sqlite_web /path/to/database.db
```

### Features

* Works with your existing SQLite databases, or can be used to create new databases.
* Add or drop:
  * Tables
  * Columns (yes, you can drop and rename columns!)
  * Indexes
* Export data as JSON or CSV.
* Import JSON or CSV files.
* Browse table data.

### Command-line options

The syntax for invoking sqlite-web is:

```sh
$ sqlite_web [options] /path/to/database-file.db
```

The following options are available:

* ``-p``, ``--port``: default is 8080
* ``-H``, ``--host``: default is 127.0.0.1
* ``-d``, ``--debug``: default is false
* ``-x``, ``--no-browser``: do not open a web-browser when sqlite-web starts.
