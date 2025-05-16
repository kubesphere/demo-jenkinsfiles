## Usage
1. In devops project, create a `Username and Password` credential for your dockerhub(or other image registry) repository.
2. In devops project, create a `Secret Text` or `kubeconfig` credential for your kubeconfig.
3. Modify the environment variables defined in the [Jenkinsfile](./Jenkinsfile) to match the credentials you created in above steps.
4. In devops project, create a `Multi-branch Pipeline` pointing to this Jenkinsfile and run it.
