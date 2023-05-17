# Global Azure 2023 - Azure Static Web Apps in 45 mins

This repository contains a simple [Hugo](https://gohugo.io) website that can be deployed continuously to an instance of Azure Static Web App. All you need to do is provisioning a new instance of Azure Static Web App and generate an API token.

Store the API token in GitHub as "Action Secret" and name it `AZURE_STATIC_WEB_APPS_API_TOKEN`.

The [existing action](./.github/workflows/ci-cd.yml) will automatically build the website and deploy it to your instance of Azure Static Web App once you push to the `main` branch.

Preview deployments will be created for every pull request (PR) against the `main` branch.
