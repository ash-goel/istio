<<<<<<< HEAD
k get vs --all-namespaces
kubectl get gateway --all-namespaces\n
k apply -f deploy-hello-world.yaml
k apply -f deploy-hello-world.yaml
k apply -f svc-hello-world.yaml
export ns=istio-test
alias k='kubectl -n=$ns'
k get gateway
k get svc -l=istio=ingressgateway -n istio-system

download Istio
curl -sL https://istio.tetratelabs.io/getmesh/install.sh | bash

install demo profile
=======
# istio
>>>>>>> f3c20f8424f980fa0404746e1c70b31ca9ba2b1b
