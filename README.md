# glibc_builder64
prebuilt debug libc for study

### how to use

```
docker pull skysider/glibc_builder64:${glibc_version}
```

compiled libc.so is located in `/glibc/${glibc_version}/64/lib/` . 

### supported libc version

- 2.19
- 2.23
- 2.24
- 2.26
- 2.27
- 2.28
- 2.29
- 2.30
- 2.31

besides, you can also build your own glibc version with following command:

```shell
docker build --build-arg GLIBC_VERSION=${version} -t <tag> .
```

