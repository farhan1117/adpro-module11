# adpro-module11

## Reflections

### Reflection on Hello Minikube

1. Jumlah log yang didapat setelah membuka app berkali-kali bertambah karena adanya request GET baru yang masuk ke dalam server.
2. Tujuan dari penggunaan `-n` ketika `kubectl get` adalah untuk menentukan namespace, pada tutorial ini adalah kube-system yang berisi pod (hello-node) yang digunakan oleh server kubernetes it sendiri.


### Reflection on Rolling Update & Kubernetes Manifest File

1. Pada kubernetes, perbedaan dari Rolling Update dan Recreate update adalah cara menangani update tersebut. Dimana Rolling update melakukan update dengan bertahap dengan menghentikan dan membuat pod baru secara bergantian. Sebaliknya Recreate menghentikan semua pod lama sebelum membuat pod baru dan menyebabkan adanya downtime pada proses update.
