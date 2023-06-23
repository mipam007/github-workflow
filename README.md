# github-workflow
various GitHub Actions workflows

## dev-prod-gcp.yml
GCP WIF GitHub Actions integration. Do the Terraform deploy. After pull-request is reviewed and merged from feature branch to DEV branch validate and plan job starts. Plan job ends after artifact is created. Apply/deploy job is triggered by user/on-click. After testing your GCP infra, pull-request from DEV to PROD should happen and after merge, same job scenario as in DEV starts.   
