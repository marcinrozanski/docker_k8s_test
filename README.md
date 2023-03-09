# docker_k8s_test

Build files for https://hub.docker.com/r/rozanski/testrepo1

```console
docker run -d -p 80:80 rozanski/testrepo1
```
or
```console
wget https://raw.githubusercontent.com/marcinrozanski/docker_k8s_test/master/test_k8_deploy.yaml -o test_k8_deploy.yaml
kubectl apply -f test_k8_deploy.yaml
```