# CI-CD-Templates
CI/CD Templates with jenkins, gitlab-ci, github actions workflow and azure pipelines.

There would be two groups of pipeline files for a Project Repository with a frontend folder (for the react code) & backend folder (for the django code). These microservices would be built in docker containers and there would be a dockerfile in both the frontend and backend folder.
Group 1 would be pipeline configurations to complete the following:
1. Perform unit tests for the frontend react application and the backend django application. 
2. Build and push docker images of the frontend and backend applications to a container registry.
3. SSH into a remote linux server and deploy the containers on the server.

Group 2 would be pipeline configurations to do the following:
1. Perform unit tests for the frontend react application and the backend django application. 
2. Build and push docker images of the frontend and backend applications to a container registry.
3. Connect to a kubernetes cluster and deploy a helm chart or the manifest files with the configurations for the microservices (deployments, services, ingress, etc)
