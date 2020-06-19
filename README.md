# gcp iam costume roles by code

gcloud iam roles create role-id --project=project-id --file=yaml-file-path

#### example
gcloud iam roles create PushContainerRegistry --project=project-id --file=gcr-push-pull-only.yaml
