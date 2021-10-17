# Задание 1: Подготовить инвентарь kubespray

Для решения данной задачи был поднят локальный кластер виртуальных машин, далее подготовлен [hosts,yaml](hosts.yaml).
<br>Кроме того, для изменения CRI на containerd в файле group_vars/k8s_cluster/k8s-cluster.yml был изменён параметр container_manager: containerd а в файле group_vars/etcd.yml параметр etcd_deployment_type: host   
<br> После этого запустил плейбуку и проверил статус нод в кластере.
![nodes](nodes.png)

