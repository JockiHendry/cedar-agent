This is an experimental fork of the original [Cedar-Agent](https://github.com/permitio/cedar-agent) repository.  This repository updates Cedar's version to 4.9.1.

### How To Use

The image is pushed to Docker Hub as `jockihendry/cedar-agent` with tag like `build-20250420`.  For standalone usage, run the following command:

```
docker run --rm -p 8180:8180 jockihendry/cedar-agent:latest
```

Then open the following URL in a browser to verify that it is working properly: http://localhost:8180/swagger-ui.

To use Cedar Agent with Cedar 4.9.1 as OPAL Client, use the following image: `jockihendry/opal-client-cedar:0.9.4-patch1` (see <https://github.com/jockihendry/opal> for more information).