# Practice K8s

### Pod

- Define a Command and Arguments for a Container

```yaml

apiVersion: v1
kind: Pod
metadata:
  name: pod_with_port_exposed
  labels:
    app: dev
spec:
  containers:
  - image: nginx
    name: myPod
    ports:
    - containerport: 80


```
