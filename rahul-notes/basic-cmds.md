# For check namespace
$ kubectl get ns
---------------------
# For check Running Pods
$ kubectl get pods -n nginx 
							here: -n for namespace and nginx is namespace name
--------------------
# For run a yml file 
$ kubectl apply -f <filename.yml>
---------------------
# Stop running yml file
$ kubectl delete -f <filename.yml>
---------------------