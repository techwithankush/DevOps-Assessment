# DevOps-Assessment

1. Fork the provided GitHub repository into your personal GitHub account.

2. Create a Dockerfile in the project that builds a Docker image for the Node.js application.

3. Set up Minikube locally or provision a Kubernetes cluster in a cloud provider such as AWS, Azure, or GCP.

4. Choose either GitHub Actions, BitBucket Pipeline, or Jenkins. Configure the selected CI/CD tool to trigger builds on code changes, build Docker images, and push them to a container registry.

5. Create a Kubernetes manifest files for the Node.js application.

6. Integrate your CI/CD tool with Kubernetes, ensuring that code changes trigger a build, Docker images are pushed to the registry, and the application is deployed to the Kubernetes cluster.

7. Deploy an Ingress controller (e.g., Nginx, Envoy) in your Kubernetes cluster. Write an Ingress resource to map external traffic to the Node.js service.


Interview Demonstration:
During the interview, be prepared to demonstrate the entire CI/CD pipeline:

1. Show that the CI/CD tool correctly triggers builds on code changes.
2. Verify that Docker images are built and pushed to the registry.
3. Demonstrate the deployment of the updated application to the Kubernetes cluster.
4. Confirm that the Ingress controller is correctly routing traffic to the Node.js service.


Note:
To expedite the interview process, avoid deleting any essential resources, such as EC2 instances, Kubernetes clusters, or Minikube instances, to ensure a smooth demonstration of the CI/CD pipeline.
