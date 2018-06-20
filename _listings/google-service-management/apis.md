---
name: Google Service Management
x-slug: google-service-management
description: Google Service Management is an infrastructure service of Google Cloud
  Platform that manages other APIs and services, including Googles own Cloud Platform
  services and their APIs, and services created using Google Cloud Endpoints.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: History
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/history/master/_listings/google-service-management/apis.md
specificationVersion: "0.14"
apis:
- name: Google Service Management API Get History
  x-api-slug: google-service-management-api
  description: |-
    Lists the history of the service configuration rollouts for a managed
    service, from the newest to the oldest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/service-management/overview
  baseURL: ://servicemanagement.googleapis.com////v1/services/{serviceName}/rollouts
  tags: Service History
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/history/master/_listings/google-service-management/v1servicesservicenamerollouts-get-openapi.md
- name: Google Service Management API
  x-api-slug: google-service-management-api
  description: Google Service Management is an infrastructure service of Google Cloud
    Platform that manages other APIs and services, including Googles own Cloud Platform
    services and their APIs, and services created using Google Cloud Endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-icon.png
  humanURL: https://cloud.google.com/service-management/overview
  baseURL: ://servicemanagement.googleapis.com//
  tags: History
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/history/master/_listings/google-service-management/openapi.md
x-common:
- type: x-change-log
  url: https://cloud.google.com/service-management/release-notes
- type: x-code
  url: https://cloud.google.com/service-management/libraries
- type: x-command-line-interface
  url: https://cloud.google.com/sdk/gcloud/reference/beta/service-management/
- type: x-rate-limits
  url: https://cloud.google.com/service-management/quota
- type: x-support
  url: https://cloud.google.com/service-management/support
- type: x-website
  url: https://cloud.google.com/service-management/overview
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---