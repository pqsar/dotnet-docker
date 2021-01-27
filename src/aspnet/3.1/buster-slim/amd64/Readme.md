# .NET CORE IMAGE
[![Docker Repository on Quay](https://quay.io/repository/pqsdev/mssql-tools/status "Docker Repository on Quay")](https://quay.io/organization/pqsdev)

Custom .NET CORE image including System.Drawing native dependencies

## Build

Clone the repo and :

```bash
docker build -f  Dockerfile -t quay.io/pqsdev/aspnet:3.1-buster-slim .
```


## Using this image

**Available on [quay.io](https://quay.io/repository/pqsdev/mssql-tools)**

This commands returns an interactive console inside the pod
```bash
oc run -i -t mssql-tools --image=quay.io/pqsdev/aspnet:3.1-buster-slim
```
