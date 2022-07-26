# superset multiarch

Builds and publishes an [Apache Superset](https://superset.apache.org) container image which works on amd64 and aarch64.

```bash
docker run \
    --name superset \
    -p 8080:8088 \
    ghcr.io/tgrosinger/superset-multiarch:latest
```

Then open http://localhost:8080.
