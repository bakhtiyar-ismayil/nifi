# nifi


Get information from https://hub.docker.com/r/apache/nifi


```
docker run --name nifi -p 8443:8443 -d apache/nifi:latest
```

```
docker logs nifi | grep Generated
```

```
docker run --name nifi -p 9443:9443  -d -e NIFI_WEB_HTTPS_PORT='9443' apache/nifi:latest
```

```
docker run --name nifi -p 8443:8443 -d -e SINGLE_USER_CREDENTIALS_USERNAME=admin -e SINGLE_USER_CREDENTIALS_PASSWORD=ctsBtRBKHRAx69EqUghvvgEvjnaLjFEB apache/nifi:latest
```

