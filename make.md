- download jdk
```
curl -sL --retry 3 --insecure \
--header "Cookie: oraclelicense=accept-securebackup-cookie;" \
"https://download.oracle.com/otn-pub/java/jdk/8u201-b09/42970487e3af4f5aa5bca3f542482c60/jdk-8u201-linux-x64.tar.gz"
```

- step 1: git clone
```shell
git clone https://github.com/iogogogo/docker-spark.git
```

- step 2: build image
```shell
docker build -t sharplook/spark:1.0 .
```
- step 3:docker-compose up -d
```shell
docker-compose up -d
```

- docker ps

```shell

```

