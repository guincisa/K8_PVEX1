# K8_PVEX1

two random persistent volumes on a pod
/mnt/data -> /usr/share/nginx/html
/mnt/data2 -> /tmp

pv-deployment.yaml
this replaces pv-pod.yaml
and will deploy on named node
      nodeName: real-k8-1

