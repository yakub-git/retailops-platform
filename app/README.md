RetailOps Platform



Project Overview



RetailOps Platform is a sample retail operations application built using Node.js, Docker, and Kubernetes.



Technologies Used



\- Node.js

\- Docker

\- Kubernetes

\- Git

\- GitHub



Features



\- Containerized application using Docker

\- Kubernetes Deployment and Service

\- Version control using Git and GitHub



Project Structure



\- Dockerfile

\- index.js

\- package.json

\- deployment.yaml

\- service.yaml



Commands Used



Build Docker Image



docker build -t retailops-app .



Run Docker Container



docker run -p 3000:3000 retailops-app



Kubernetes Deployment



kubectl create deployment retailops --image=retailops-app



Kubernetes Service



kubectl expose deployment retailops --type=NodePort --port=3000



Author



Syed Yakub



