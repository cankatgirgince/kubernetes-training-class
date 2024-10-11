# kubectl pods komutları

İşte **`kubectl` pod komutlarının** tablo halinde bir özeti:

| **Komut**                                         | **Açıklama**                                                                 |
|---------------------------------------------------|------------------------------------------------------------------------------|
| `kubectl get pods`                                | Tüm pod'ları listele                                                         |
| `kubectl get pods -n <namespace>`                 | Belirli bir namespace'teki pod'ları listele                                  |
| `kubectl describe pod <pod-ismi>`                 | Belirli bir pod'un ayrıntılarını görüntüle                                    |
| `kubectl get pods -o wide`                        | Pod'ları genişletilmiş formatta (IP, düğüm bilgisiyle) listele                |
| `kubectl get pods --all-namespaces`               | Tüm namespace'lerdeki pod'ları listele                                       |
| `kubectl logs <pod-ismi>`                         | Belirli bir pod'un günlüklerini görüntüle                                     |
| `kubectl logs <pod-ismi> -c <container-ismi>`     | Pod'daki belirli bir container'ın günlüklerini görüntüle (çoklu container'lar için) |
| `kubectl logs -f <pod-ismi>`                      | Pod günlüklerini sürekli izle (tail logs)                                    |
| `kubectl delete pod <pod-ismi>`                   | Belirli bir pod'u sil                                                        |
| `kubectl apply -f <pod-dosya.yaml>`               | Bir pod'u YAML dosyasından oluştur veya güncelle                             |
| `kubectl run <pod-ismi> --image=<image-ismi> --restart=Never` | Geçici bir pod çalıştır (örneğin, debugging için)                     |
| `kubectl exec -it <pod-ismi> -- /bin/bash`        | Pod içinde bir shell'e erişim sağla (bash)                                    |
| `kubectl port-forward pod/<pod-ismi> <local-port>:<pod-port>` | Bir pod'a port yönlendirme yaparak yerel bağlantı kur                     |
| `kubectl cp <local-path> <pod-ismi>:/<path-in-pod>` | Yerel dosyayı bir pod'a kopyala                                              |
| `kubectl top pod <pod-ismi>`                     | Belirli bir pod'un CPU ve bellek kullanımını görüntüle                       |

Bu komutlar, Kubernetes'teki pod'ları yönetmek ve bilgi almak için sıkça kullanılır.
