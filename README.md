Changelog
===========
**19.10.2015:** Update to LocomotiveCMS Engine v3.0.0.rc1

Usage
===========

Right now this is early alpha! Do **not** use in production if you're not sure, what you do!



Mongo-DB Link
-----------

Use with official mongo image:

    docker run -d --name locomotive_mongo mongo

Then run with:

    docker run -d --link locomotive_mongo:mongo 42nerds/locomotive