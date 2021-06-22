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
* [WSGI for Web Developers (Ryan Wilson-Perkin)](https://www.youtube.com/watch?v=WqrCnVAkLIo)
* [The ultimate guide to enabling Cross-Origin Resource Sharing (CORS)](https://blog.logrocket.com/the-ultimate-guide-to-enabling-cross-origin-resource-sharing-cors/)


# API development

* [Handling File Uploads With Flask](https://blog.miguelgrinberg.com/post/handling-file-uploads-with-flask)


# Cloud storage

* [Uploading objects](https://cloud.google.com/storage/docs/uploading-objects#storage-upload-object-python)


# Deploying ML models

* [Model Serving in PyTorch](https://pytorch.org/blog/model-serving-in-pyorch/)
* [PyTorch - SAVING AND LOADING MODELS](https://pytorch.org/tutorials/beginner/saving_loading_models.html)
* [Serving your Machine Learning model in Google Cloud Platform with Python, Docker & Kubernetes](https://medium.com/data-science-from-signify-research-eindhoven/serving-your-machine-learning-model-in-google-cloud-platform-with-python-docker-kubernetes-e8c8b2f8a932)


# Création d'entreprise

* [Le guide de l'entrepreneur](https://www.kiwili.com/wp-content/uploads/dlm_uploads/2018/11/guide_de_lentrepreneur_kiwili.pdf)


# Google Cloud Platform

* [GCP Free Tier](https://cloud.google.com/free/docs/gcp-free-tier#free-tier)


# Canvas API

* [HTML5 Canvas Tutorial for Beginners | An Intro to Becoming a Pro - Ep. 1](https://www.youtube.com/watch?v=EO6OkltgudE)
* [Pixel manipulation with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Pixel_manipulation_with_canvas)
* [Blending two images with HTML5 canvas](https://www.tutorialspoint.com/Blending-two-images-with-HTML5-canvas)


# Misc.

```
$ gcloud builds --project PROJECT-ID submit --tag gcr.io/PROJECT-ID/flask-app:v1 .
$ gcloud container clusters get-credentials CLUSTERNAME --region REGION --project PROJECT-ID
$ kubectl describe deployment flask-app
$ nano app.yaml
$ kubectl apply -f app.yaml
$ kubectl expose deployment flask-app --type=LoadBalancer --port 8081 --target-port 8081
$ kubectl get svc
```
