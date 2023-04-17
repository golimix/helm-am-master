# helm-starter-base
helm version
version.BuildInfo{Version:"v3.11.3", GitCommit:"323249351482b3bbfc9f5004f65d400aa70f9ae7", GitTreeState:"clean", GoVersion:"go1.20.3"}
# helm-am-master

```bash
helm starter fetch git@github.com:golimix/helm-starter-base.git
helm create am-master --starter helm-starter-base
```

# helm-am-proxy

```bash
helm starter fetch git@github.com:golimix/helm-starter-base.git
helm create am-proxy --starter helm-starter-base
```


# TODO
* helm包不需要暴露service端口的
* am-proxy是需要添加探针的