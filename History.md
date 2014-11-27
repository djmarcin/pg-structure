Note
----
Version history for minimal documentation updates are not listed here to prevent cluttering.
Important documentation changes are included anyway.

1.3.0 / 2014-11-27
==================
* Parameter validation added to pg-structure main function. This would ease debugging.
* Fix: pg-structure.generate function was throwing error, now it calls its callback with error
if database connection error occurs.

1.2.1 / 2014-11-26
==================
* Fix: Documentation updated for 1.2

1.2.0 / 2014-11-26
==================
* Fix: pg-structure callback does not get error object. Instead error is thrown. Now callback gets error object as its first parameter as expected.
* db.schema() function now throws more informative error if referenced schema is not found in db and also not in the options of requested schemas.
* db.schemaExist() function added.
* History.md file added. (This file)

1.1.0 / 2014-11-25
==================
* table.foreignKeyConstraintExist() function added.

1.0.0 / 2014-11-25
==================
* Completely rewritten to migrate from plain object to object oriented design.