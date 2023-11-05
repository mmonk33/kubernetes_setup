# Install k8s cluster with Kubespray on Yandex Cloud
# kubernetes_setup 

В примере использован первый вариант - полуавтоматический.
Но тестировался и полностью автоматический. 
Полуавтоматический вариант выбран для более полного контроля и дебагинга развёртывания кластера с учетом будущих возможных изменений в версиях.

## Create cloud resources and install k8s cluster
```
$ /opt/kubernetes_setup/cluster_install.sh
```

## Delete cloud resources
```
$ /opt/kubernetes_setup/cluster_destroy.sh
```

Результаты разворачивания инфрастурктуры и кластера:

![Установка кластера k8s](https://github.com/MikhailRyzhkin/kubernetes_setup/assets/69116076/f5398dfe-74e4-4614-b9b9-8670fac5c9de)


Полезные ссылки:

## Register in Yandex Cloud

https://cloud.yandex.ru

## Install Terraform client 

https://learn.hashicorp.com/terraform/getting-started/install
 https://cloud.yandex.ru/docs/tutorials/infrastructure-management/terraform-quickstart

## Install Ansible

https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

## Install Kubectl

https://kubernetes.io/docs/tasks/tools/install-kubectl/

## Install Helm

https://helm.sh/docs/intro/install/

## Install jq (small CLI utility for JSON parsing)

https://stedolan.github.io/jq/

## Clone Kubespray repo and install Kubespray requirements
```
$ git clone https://github.com/MikhailRyzhkin/kubernetes_setup
cd /kubernetes_setup
$ git clone https://github.com/MikhailRyzhkin/kubespray
```
