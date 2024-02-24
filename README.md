1. Create EKS
2. Configure a Database
Set up a Postgres database using a Helm Chart. Using port forward to run SQL query for creating new table and inserting dummy data.
3. Created a new repository on ECR
4. Creted a repository on github
5. Create CodeBuild to build and configured it with github merge request
6. Pushed API code with docker file and buildspec.yaml file to github which created a image file in repository
7. Created deployment files and execute kubectl commands to deployed the code from ECR 
Related to:
Deployment and services: deployment\analytics-api.yaml
ConfigMap for un-security env: deployment\env-congifmap.yaml
Secret for security env: deployment\env-secret.yaml
8. Configuring CloudWatch Insights