PostgresAdapter
============
This is an adapter for the [Dart ActiveRecord implementation](https://github.com/Adracus/ActiveRecord).
It is based on xxgregs [postgres adapter for Dart](https://github.com/xxgreg/postgresql).

Instantiate a postgres adapter via its constructor. The constructor needs a uri in the
following form:

    postgres://<username>:<password>@<host>:<port>/<database>
    
The postgres adapter is also capable of some _raw_ postgres actions through the modelsWhere-method.
Via this method, it is possible to harness the full power of the postgres database.