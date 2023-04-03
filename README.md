# Домашнее задание к занятию «Kubernetes. Причины появления. Команда kubectl»
1. MicroK8S установлен:  
   ![microk8s status](./pictures/microk8s%20status.PNG)  
   Dashboard установлен:  
   ![enable dashboard](./pictures/enable%20dashboard.PNG)  
   Генерация сертификата после добавления внешнего IP адреса в файл ```/var/snap/microk8s/current/certs/csr.conf.template```:  
   ![certgen](./pictures/certgen.PNG)  

2. Kubectl установлен:  
   ![kubectl version](./pictures/kubectl%20version.PNG)  
   Конфиг для kubectl получил при помощи команды ```microk8s config```:  
   ![kubectl config](./pictures/kubectl%20config.PNG)  
   И успешно подключился:  
   ![kubectl get nodes](./pictures/kubectl%20get%20nodes.PNG)  
   Открыл Dashboard наружу не при помощи Port-forward, а изменив сервис дашборда на Nodeport:  
   ![kubectl get services](./pictures/kubectl%20get%20services.PNG)  
   И успешно подключился к дашборду по внешнему ip адресу сервера:  
   ![dashboard](./pictures/dashboard.PNG)