# Postgres 18 + pgvector Dockerfile

Builds PostgreSQL 18 (stable) with pgvector from source for deployment.

To use, clone this repo locally, open a terminal in the repo directory and run `docker compose up -d --build`.

 Important!  This performs a basic build of Postgres using the default configuration.  If want to enabled additional features you can tweak the build by following the [Postgres build documentation](https://www.postgresql.org/docs/18/install-make.html).