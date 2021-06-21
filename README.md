# Resources

# Kubernetes

* [Introducing GKE Autopilot: a revolution in managed Kubernetes](https://cloud.google.com/blog/products/containers-kubernetes/introducing-gke-autopilot)
* [Creating an Autopilot cluster](https://cloud.google.com/kubernetes-engine/docs/how-to/creating-an-autopilot-cluster)
* [GKE Quickstart](https://cloud.google.com/kubernetes-engine/docs/quickstart)
* [Deploying a stateless Linux application](https://cloud.google.com/kubernetes-engine/docs/how-to/stateless-apps)
* [A Guide to Deploy Flask App on Google Kubernetes Engine](https://medium.com/google-cloud/a-guide-to-deploy-flask-app-on-google-kubernetes-engine-bfbbee5c6fb)
* [A step by step guide for deploying flask web services on GKE cluster](https://medium.com/@kekayan/a-step-by-step-guide-for-deploying-flask-web-services-on-gke-cluster-76420d75671d)
* [Install and Set Up kubectl on Linux](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)
* [minikube start](https://minikube.sigs.k8s.io/docs/start/)

# Web development

* [gunicorn](https://gunicorn.org/)


# Cloud storage

* [Uploading objects](https://cloud.google.com/storage/docs/uploading-objects#storage-upload-object-python)


# Création d'entreprise

* [Le guide de l'entrepreneur](https://www.kiwili.com/wp-content/uploads/dlm_uploads/2018/11/guide_de_lentrepreneur_kiwili.pdf)

```
$ gcloud builds --project PROJECT-ID submit --tag gcr.io/PROJECT-ID/flask-app:v1 .
$ gcloud container clusters get-credentials CLUSTERNAME --region REGION --project PROJECT-ID
$ kubectl describe deployment flask-app
$ nano app.yaml
$ kubectl apply -f app.yaml
$ kubectl expose deployment flask-app --type=LoadBalancer --port 8081 --target-port 8081
$ kubectl get svc
```
