---
name: Azure Resource Manager
description: Azure Resource Manager enables you to deploy and manage the infrastructure
  for your Azure solutions. You organize related resources in resource groups, and
  deploy your resources with JSON templates. For an introduction to deploying and
  managing resources with Resource Manager, see Azure Resource Manager overview.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
x-kinRank: "8"
x-alexaRank: ""
tags:
- Resources
- Microsoft
- Links
- Deployment
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/geo/master/_listings/azure-resource-manager/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure Resource Manager API
  description: Azure Resource Manager enables you to deploy and manage the infrastructure
    for your Azure solutions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Geo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/geo/master/_listings/azure-resource-manager/subscriptions-subscriptionid-locations-get.md
- name: Azure Resource Manager API Gets all available geo-locations.
  description: This operation provides all the locations that are available for resource
    providers; however, each resource provider may support a subset of this list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: http:://management.azure.com//
  tags: Geo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/geo/master/_listings/azure-resource-manager/subscriptions-subscriptionid-locations-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/geo/master/_listings/azure-resource-manager/subscriptions-subscriptionid-locations-get-postman.md
x-common:
- type: x-website
  url: https://docs.microsoft.com/en-us/rest/api/resources/
- type: x-website
  url: https://docs.microsoft.com/en-us/rest/api/resources/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---