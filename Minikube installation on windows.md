# Installation of minikube on windows
## Pre-requisites
Install docker-desktop by following the link 
https://docs.docker.com/desktop/setup/install/windows-install/

After installing docker desktop restart your system 
# Now download minikube installer by following the below link
https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download
- After installing minikube 
- close all terminals 
- Now search for dokcer destop app and start it 
- Check if docker docker engine is in running state (this can be shown in the dokcer destop app)
- Now open the terminal and execute the command minikube status and see the status 
- Now you can start the minikube using **minikube start** (this will start only if the docker engine is in running state)
- Now check the status of minikube uusing **minikube status**
- Try executing few kubectl commands "kubectl get pods" "kubectl get all" for verification
