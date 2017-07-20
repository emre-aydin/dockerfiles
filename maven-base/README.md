To build:

```bash
 docker build -t mvn-base .
```

To run:

```bash
docker run -it -e LOCAL_USER_ID=`id -u $USER` mvn-base mvn --version
```
