Container image with postgresql client tools.

To execute postgresql command line tools inside docker or Kubernetes.

Alpine based image, with postgresql-client and some other tools installed.

Default entry point is `psql` command, but other tools like `pg_isready`, `createdb` and `createuser` are available.

```console
docker run --rm --interactive --tty ghcr.io/momentum-xyz/postgresql-client:latest --host db --user root -p
```
