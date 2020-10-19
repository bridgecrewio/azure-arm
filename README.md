# azure-arm

Sample setup with Azure Pipelines to scan ARM templates with Bridgecrew, only deploying them if no issues are found.

This is not meant to be a production-grade deployment pipeline; for example, many values, such as the resource group name, are hardcoded. Rather, this is intended as a simple example of what a CI / CD flow using Bridgecrew looks like.
