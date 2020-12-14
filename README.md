# kube-dockerfile
1.20.0

```shell
sudo docker pull registry.cn-hangzhou.aliyuncs.com/xbz_k8s/kube-apiserver:v1.20.0
docker tag registry.cn-hangzhou.aliyuncs.com/xbz_k8s/kube-apiserver:v1.20.0 k8s.gcr.io/kube-apiserver:v1.20.0

sudo docker pull registry.cn-hangzhou.aliyuncs.com/xbz_k8s/coredns:1.7.0
docker tag registry.cn-hangzhou.aliyuncs.com/xbz_k8s/coredns:1.7.0 k8s.gcr.io/coredns:1.7.0

sudo docker pull registry.cn-hangzhou.aliyuncs.com/xbz_k8s/etcd:3.4.13-0
docker tag registry.cn-hangzhou.aliyuncs.com/xbz_k8s/etcd:3.4.13-0 k8s.gcr.io/etcd:3.4.13-0

sudo docker pull registry.cn-hangzhou.aliyuncs.com/xbz_k8s/kube-controller-manager:v1.20.0
docker tag registry.cn-hangzhou.aliyuncs.com/xbz_k8s/kube-controller-manager:v1.20.0 k8s.gcr.io/kube-controller-manager:v1.20.0

sudo docker pull registry.cn-hangzhou.aliyuncs.com/xbz_k8s/kube-proxy:v1.20.0
docker tag registry.cn-hangzhou.aliyuncs.com/xbz_k8s/kube-proxy:v1.20.0 k8s.gcr.io/kube-proxy:v1.20.0

sudo docker pull registry.cn-hangzhou.aliyuncs.com/xbz_k8s/kube-scheduler:v1.20.0
docker tag registry.cn-hangzhou.aliyuncs.com/xbz_k8s/kube-scheduler:v1.20.0 k8s.gcr.io/kube-scheduler:v1.20.0

sudo docker pull registry.cn-hangzhou.aliyuncs.com/xbz_k8s/pause:3.2
docker tag registry.cn-hangzhou.aliyuncs.com/xbz_k8s/pause:3.2 k8s.gcr.io/pause:3.2
```