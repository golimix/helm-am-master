# helm-starter-base
helm version
version.BuildInfo{Version:"v3.11.3", GitCommit:"323249351482b3bbfc9f5004f65d400aa70f9ae7", GitTreeState:"clean", GoVersion:"go1.20.3"}
# helm-am-master

```bash
helm starter fetch git@github.com:golimix/helm-starter-base.git
helm create am-master --starter helm-starter-base
helm repo update am
helm pull am/am-master --version=0.1.1
```

# helm-am-proxy

```bash
helm starter fetch git@github.com:golimix/helm-starter-base.git
helm create am-proxy --starter helm-starter-base

# 安装am-proxy库文件
helm upgrade -i am-proxy am/am-proxy -n limix-system
```


# TODO
* helm包不需要暴露service端口的
* am-proxy是需要添加探针的



# DONE
* 容器安全访问账户信息没有添加到helm包当中