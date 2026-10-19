To run my first app inside Kubernetes and access it:

Docker Desktop was Installed
Minikube was installed
Steps involved:

Start a local Kubernetes cluster with Minikube: minikube start
Create your first Pod (using Nginx image): kubectl run hello-k8s --image=nginx --port=80
Verify the Pod is running: kubectl get pods
Expose the Pod as a Service: kubectl expose pod hello-k8s --type=NodePort --port=80
Open the app in your browser: minikube service hello-k8s

<img width="1600" height="840" alt="WhatsApp Image 2026-10-19 at 15 12 11" src="https://github.com/user-attachments/assets/a7a02ccf-0451-4705-825d-dc04d73e1d98" />

<img width="1600" height="832" alt="image" src="https://github.com/user-attachments/assets/befa6c87-8a33-4ee6-aa58-5f4039ade210" />




