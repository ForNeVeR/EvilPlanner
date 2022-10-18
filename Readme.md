EvilPlanner [![Status Zero][status-zero]][andivionian-status-classifier]
===========

**NOTE:** the project has been merged into [fornever.me][].

EvilPlanner is a small lab application.

Features
--------

Currently it will only output the random quote from Evil Overlord List (see
quotation source for every quote near the quote itself).

Database Setup
--------------

EvilPlanner uses LiteDB for data storage. It will migrate its databases
automatically if necessary.

Configuration
-------------

Change `EvilPlanner.Backend/appsettings.json` file to change the application
settings.

You'll probably want to change `databasePath` parameter and point it to a
preferred location for the database.

Build
-----

You may compile the code using .NET Core SDK:

```console
$ dotnet build -c Release
```

Deployment
----------

To deploy the project, check the `docker-compose.yml` and run the following
script:

```
$ pwsh ./docker-compose.ps1
```

[andivionian-status-classifier]: https://github.com/ForNeVeR/andivionian-status-classifier#status-zero-
[fornever.me]: https://github.com/ForNeVeR/fornever.me
[status-zero]: https://img.shields.io/badge/status-zero-lightgrey.svg
