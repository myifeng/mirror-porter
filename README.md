<h1 align="center"><strong>Mirror Porter</strong></h1>

<h1 align="center">我们不生产镜像</h1>


<h1 align="center">我们只是镜像的搬运工</h1>

<br/>

## 提供gcr.io、k8s.gcr.io、quay.io、ghcr.io 等镜像中转和下载服务，一键获取你所需要的镜像

<br/>

# 使用方法

## 1. 创建[ISSUE](https://github.com/myifeng/mirror-porter/issues/new)

## 2. 标题里填写你所需要的镜像，例如 `k8s.gcr.io/kube-scheduler:v1.24.3`
## 3. 等待下载和上传完成，即可在国内通过 [`myifeng/k8s.gcr.io_kube-scheduler:v1.24.3`](https://hub.docker.com/u/myifeng) 正常使用
## 4. 更多已加速镜像请使用 [`myifeng`](https://hub.docker.com/u/myifeng)


# 规则

## 将路径中的 `/` 替换为 `_`，并在前添加`myifeng/`

| 源镜像                                                  | 加速镜像                                                        |
| ------------------------------------------------------- | --------------------------------------------------------------- |
| nginx                                                   | myifeng/nginx                                                   |
| k8s.gcr.io/kube-scheduler:v1.24.3                       | myifeng/k8s.gcr.io_kube-scheduler:v1.24.3                       |
| k8s.gcr.io/coredns/coredns:v1.8.6                       | myifeng/k8s.gcr.io_coredns_coredns:v1.8.6                       |
| k8s.gcr.io/sig-storage/csi-node-driver-registrar:v2.3.0 | myifeng/k8s.gcr.io_sig-storage_csi-node-driver-registrar:v2.3.0 |
