# 适合于墙内的镜像源，使用前请检查镜像源是否被墙

#kube-flannel  
quay-mirror.qiniu.com/coreos/flannel:v0.10.0-s390x  
quay-mirror.qiniu.com/coreos/flannel:v0.10.0-ppc64le  
quay-mirror.qiniu.com/coreos/flannel:v0.10.0-arm  
quay-mirror.qiniu.com/coreos/flannel:v0.10.0-arm64  
quay-mirror.qiniu.com/coreos/flannel:v0.10.0-amd64  


#dashboard-user-role  
image: mirrorgooglecontainers/kubernetes-dashboard-amd64:v1.10.0  
path: /home/share/certs  
nodePort: 12582  
