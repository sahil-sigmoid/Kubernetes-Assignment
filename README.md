# Kubernetes-Assignment

-> minikube start 

-> minikube mount ./dags/:/mnt/airflow/dags 

Open new terminal 

-> kubectl get pods,deploy,svc,pv,pvc 

-> ./script-apply.sh 

-> minikube service airflow-webserver 

Open new terminal 

-> kubectl port-forward svc/airflow-webserver 8080:8080
