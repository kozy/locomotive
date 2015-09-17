Usage
===========

Right now this is early alpha! Do **not** use in production if you're not sure, what yo do!

Mongo-DB Link
-----------

Use with official mongo image:

    docker run -d --name locomotive_mongo mongo

Then run with:

    docker run -d --link locomotive_mongo:mongo 42nerds/locomotive