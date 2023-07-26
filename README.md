# ApacheSuperset


Install Superset on your Laptop : https://superset.apache.org/docs/installation/running-on-kubernetes/

Prerequisites : Docker Desktop + Kubernetes

Steps to install : 
1.	Launch PowerShell
2.	helm upgrade --install --values superset.yaml superset superset/superset
    a.	PFA file attached. 
3.	kubectl port-forward service/superset 8088:8088
4.	Open Chrome and login to superset : 127.0.0.1:8080 admin/admin
5.	Import dashboards
    a.	PFA files attached.
