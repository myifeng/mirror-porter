<h1 align="center"><strong>Mirror Porter</strong></h1>

<h1 align="center">不生产镜像</h1>


<h1 align="center">只是镜像的搬运工</h1>

<br/>

## Mirror Porter提供gcr.io、k8s.gcr.io、quay.io、ghcr.io 等镜像中转和下载服务
## 国外仓库无法访问？ 代理下载速度异常缓慢？国内构建版本不全？找不到想要的版本？
## 拒绝重新构建，只拉取官方镜像，可校验sha值，完美还原
## 秒传镜像，不再苦苦等待进度条，一键获取你所需要的镜像

<br/>

# 使用方法

## 1. 先在[`myifeng`](https://hub.docker.com/u/myifeng)中搜索自己需要的镜像和版本，如果有可以直接使用
## 2. 如果仓库没有自己需要的镜像，则可以创建[ISSUE](https://github.com/myifeng/mirror-porter/issues/new)进行搬运
## 3. 标题里填写你所需要的镜像，例如 `k8s.gcr.io/kube-scheduler:v1.24.3`
## 4. 自动搬运成功后，即可在国内通过 [`myifeng/k8s.gcr.io_kube-scheduler:v1.24.3`](https://hub.docker.com/u/myifeng) 正常使用
## 5. 更多已加速镜像请使用 [`myifeng`](https://hub.docker.com/u/myifeng)


# 匹配规则

## 将路径中的 `/` 替换为 `_`，并在前添加`myifeng/`,即可对应加速后的镜像
## 将路径中的 `_` 替换为 `/`，删去开头的`myifeng/`,即可还原源镜像

| 源镜像                                                  | 加速镜像                                                        |
| ------------------------------------------------------- | --------------------------------------------------------------- |
| nginx                                                   | myifeng/nginx                                                   |
| k8s.gcr.io/kube-scheduler:v1.24.3                       | myifeng/k8s.gcr.io_kube-scheduler:v1.24.3                       |
| k8s.gcr.io/coredns/coredns:v1.8.6                       | myifeng/k8s.gcr.io_coredns_coredns:v1.8.6                       |
| k8s.gcr.io/sig-storage/csi-node-driver-registrar:v2.3.0 | myifeng/k8s.gcr.io_sig-storage_csi-node-driver-registrar:v2.3.0 |
