# Pipeline description

After pushing the code from the local machine to a github repository circleci detects the chages and starts the build pipline proccess.

# pipeline steps

The pipeline first starts by preparing the enviroment variables, then setting up node and aws cli and configure aws acces key using an already created IAM user access key  and checkout the code, after that installing the dependencies of both the frontend and the backend, then linting the frontend and after that the pipeline finishes after creating the build for both backend and frontend.
after doing all of that the admin authorizes the deployment proccess to the cloud.

