## deploy apps in locally follow below steps:

### step - 1
Make sure you installed k3s cluster locally. if not so download using below command:
```
curl -sfL https://get.k3s.io | INSTALL_K3S_VERSION=v1.29.3+k3s1 K3S_KUBECONFIG_MODE="644" sh -
```
### step - 2
Copy k3s file into config file. if you don't have .kube folder so make it and then fire below command:
```
sudo cp /etc/rancher/k3s/k3s.yaml ~/.kube/config
```

### step - 3
export KUBECONFIG env using below command:
```
export KUBECONFIG=<absolute_path_of_configfile>
```
