# githubActions-template

# name: - The name of the workflow, visible in the GitHub UI.
#on: - Specifies the events that trigger the workflow, such as push, pull_request, schedule, and workflow_dispatch.
#jobs: - Contains all the jobs that run as part of the workflow.
#build: - A job for building and testing the application.
runs-on: - Specifies the operating system for the job runner.
steps: - A sequence of steps to execute within the job.
deploy: - A job for deploying the application, dependent on the successful completion of the build job.
lint: - A job for linting code, which runs independently.
build-docker: - A job for building and pushing a Docker image.
