# Домашнее задание к занятию «Базовые объекты K8S»

### Цель задания

В тестовой среде для работы с Kubernetes, установленной в предыдущем ДЗ, необходимо развернуть Pod с приложением и подключиться к нему со своего локального компьютера. 

------

### Задание 1. Создать Pod с именем hello-world

1. Создать манифест (yaml-конфигурацию) Pod.
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Подключиться локально к Pod с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

------

### Задание 2. Создать Service и подключить его к Pod

1. Создать Pod с именем netology-web.
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web.
4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

### Решение

[pod-mia.yaml](https://github.com/murtazinilyas/02-k8s-base-objects-mia/blob/main/pod-mia.yaml)

![1-1](https://github.com/murtazinilyas/02-k8s-base-objects-mia/blob/main/screenshots/1-1.png)

![1](https://github.com/murtazinilyas/02-k8s-base-objects-mia/blob/main/screenshots/1.png)

[services.yaml](https://github.com/murtazinilyas/02-k8s-base-objects-mia/blob/main/services.yaml)

![2-1](https://github.com/murtazinilyas/02-k8s-base-objects-mia/blob/main/screenshots/2-1.png)

![2](https://github.com/murtazinilyas/02-k8s-base-objects-mia/blob/main/screenshots/2.png)

![get-pods-service](https://github.com/murtazinilyas/02-k8s-base-objects-mia/blob/main/screenshots/get-pods-service.png)
