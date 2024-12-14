# name_entity_recognition

## Workflows
    constants
    config_entity
    artifact_entity
    components
    pipeline
    app.py

## GCP Configuration

    #Gcloud cli download link: https://cloud.google.com/sdk/docs/install#windows

    gcloud init


## GCP CICD Deployment with CircleCI:
    artifact registry --> create a repository
    change line 42,50,72,76,54 in circleci config
    Opne circleci --> create a project

## Set Environment variables in CircleCI
    GCLOUD_SERVICE_KEY --> service account

    GOOGLE_COMPUTE_ZONE = asia-south1

    GOOGLE_PROJECT_ID

## Create a VM instances & setup scripts