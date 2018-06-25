---
name: Google Cloud Billing
x-slug: google-cloud-billing
description: The Google Cloud Billing API provides methods that you can use to programmatically
  manage billing for your projects in the Google Cloud Platform.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Project
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/project/master/_listings/google-cloud-billing/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Billing API Get Projects
  x-api-slug: google-cloud-billing-api
  description: |-
    Lists the projects associated with a billing account. The current
    authenticated user must be an [owner of the billing
    account](https://support.google.com/cloud/answer/4430947).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/billing/docs/
  baseURL: ://cloudbilling.googleapis.com////v1/{name}/projects
  tags: Project
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/project/master/_listings/google-cloud-billing/v1nameprojects-get-openapi.md
- name: Google Cloud Billing API
  x-api-slug: google-cloud-billing-api
  description: The Google Cloud Billing API provides methods that you can use to programmatically
    manage billing for your projects in the Google Cloud Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Generic-GCP.png
  humanURL: https://cloud.google.com/billing/docs/
  baseURL: ://cloudbilling.googleapis.com//
  tags: Project
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/project/master/_listings/google-cloud-billing/openapi.md
x-common:
- type: x-code
  url: https://cloud.google.com/billing/v1/libraries
- type: x-errors
  url: https://cloud.google.com/billing/v1/errors/core_errors
- type: x-getting-started
  url: https://cloud.google.com/billing/v1/getting-started
- type: x-how-to-guides
  url: https://cloud.google.com/billing/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/billing/v1/pricing
- type: x-website
  url: https://cloud.google.com/billing/docs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---