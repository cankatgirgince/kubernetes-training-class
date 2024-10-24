# Training
## Commands

minikube start
minikube status
kubectl get pods -A

| Komut                             | Kaynak Türü               | Açıklama                                                                                     |
|-----------------------------------|---------------------------|----------------------------------------------------------------------------------------------|
| `kubectl get pods`                | Pod                       | Kümedeki veya belirli bir ad alanındaki pod'ları listeler.                                    |
| `kubectl get services`            | Service                   | Kümedeki hizmetleri (services) listeler.                                                     |
| `kubectl get deployments`         | Deployment                | Kubernetes dağıtımlarını (deployments) listeler.                                              |
| `kubectl get replicasets`         | ReplicaSet                | Kümedeki ReplicaSet'leri (belirli bir pod setini çoğaltma işini üstlenen kontrolcü) listeler. |
| `kubectl get nodes`               | Node                      | Kümedeki düğümleri (nodes) listeler.                                                         |
| `kubectl get namespaces`          | Namespace                 | Mevcut ad alanlarını (namespaces) listeler.                                                   |
| `kubectl get configmaps`          | ConfigMap                 | ConfigMap'leri (pod konfigürasyon verilerini tutar) listeler.                                 |
| `kubectl get secrets`             | Secret                    | Gizli verileri (secrets) listeler (örn. şifreler, API anahtarları).                           |
| `kubectl get pv`                  | PersistentVolume          | Kalıcı depolama birimlerini (persistent volumes) listeler.                                    |
| `kubectl get pvc`                 | PersistentVolumeClaim     | Kalıcı depolama iddialarını (persistent volume claims) listeler.                              |
| `kubectl get ingress`             | Ingress                   | Ingress nesnelerini (HTTP ve HTTPS yük dengelemesi için giriş noktaları) listeler.             |
| `kubectl get events`              | Event                     | Kümeyle ilgili olayları (events) listeler.                                                    |
| `kubectl get daemonsets`          | DaemonSet                 | DaemonSet'leri (her node'da bir pod çalıştıran kontrolcüler) listeler.                        |
| `kubectl get statefulsets`        | StatefulSet               | StatefulSet'leri (durumlu pod'ları yönetir) listeler.                                         |
| `kubectl get jobs`                | Job                       | Kubernetes işlerini (jobs) listeler.                                                          |
| `kubectl get cronjobs`            | CronJob                   | Zamanlanmış işleri (cronjobs) listeler.                                                       |
| `kubectl get roles`               | Role                      | RBAC için rolleri (roles) listeler.                                                          |
| `kubectl get rolebindings`        | RoleBinding               | Rolleri kullanıcılar veya servis hesapları ile ilişkilendiren RoleBinding'leri listeler.       |
| `kubectl get clusterroles`        | ClusterRole               | Küme genelinde geçerli olan rolleri listeler.                                                 |
| `kubectl get clusterrolebindings` | ClusterRoleBinding        | ClusterRole'leri kullanıcılar veya servis hesapları ile ilişkilendiren bağlamaları listeler.   |
| `kubectl get endpoints`           | Endpoint                  | Service objelerine ait uç noktaları (IP adresi ve port bilgileri) listeler.                    |
| `kubectl get networkpolicies`     | NetworkPolicy             | Ağ politikalarını (network policies) listeler.                                                |








