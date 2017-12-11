# auto-deploy-gcf
Example to automatically deploy new code to GCF, using a GCB trigger

## How to
- Create a trigger on GCB using a `cloudbuild.yaml` config file similar to the
one in this repository.
- Make sure the service account used by GCB ("<PROJECT_NUM>@cloudbuild.gserviceaccount.com")
has the permission to deploy on GCF ("Cloud Functions Developer" role)
