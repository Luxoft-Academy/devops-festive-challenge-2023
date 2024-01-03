# DevOps Challenge

Welcome to our two-part DevOps Challenge. This challenge is structured into a training phase followed by the main challenge.

## Part 1: Training

The training phase is designed to teach you how to convert a Docker Compose file into Kubernetes manifests and Helm charts. 

### Training Materials

- **Folder:** `training`
- **File:** `compose.yaml` - A Docker Compose file used for training purposes.

### Training Videos

Several training videos are available, each around 20 minutes in length, detailing the conversion process:

1. [Training Video 1](https://youtu.be/3dxUbbpJ10k)
2. [Training Video 2](https://youtu.be/dJKI-BosM-g)
3. [Training Video 3](https://youtu.be/5ORP-vXzyo0)



### Access to Training Environment

To access the training environment and follow along with the videos, please send an email to Sudharsanan requesting access. 

## Part 2: Challenge

### Task: 

Deploy the Spring PetClinic application on a Kubernetes cluster. https://github.com/spring-petclinic/spring-petclinic-microservices
 
### Provided Resources:
 
Docker Images: Available at https://hub.docker.com/u/springcommunity 

Storage Class Name:  ebs

Cert Manager Issuer:  letsencrypt-prod

Ingress Controller Class Name:  nginx

Host Name: <your-username>.k8s.luxoft.academy

Kubernetes Cluster: Accessible from your practising environment. If you'd like to work locally, please, request access details via email.
 
 
### Expectations:
 
- Create Kubernetes deployment and service configurations.

- Configure persistent storage for any stateful components.

- Set up an Ingress resource using the provided ingress controller and ensure it's secured with TLS using the cert manager issuer.

- Ensure proper resource limits and requests are set for the pods.

- Include readiness probe in the deployment configuration.

- (Optional) Create MySQL StatefulSet and use in the application instead of default in memory database.

- (Optional) Implement logging and monitoring solutions.
 

## Support

If you have questions or need assistance, please refer to the training videos or contact the challenge coordinators.

We wish you the best of luck and look forward to seeing your innovative solutions!
