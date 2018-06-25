---
name: Google Cloud DNS
x-slug: google-cloud-dns
description: Google Cloud DNS is a scalable, reliable and managed authoritative Domain
  Name System (DNS) service running on the same infrastructure as Google. It has low
  latency, high availability and is a cost-effective way to make your applications
  and services available to your users. Cloud DNS translates requests for domain names
  like www.google.com into IP addresses like 74.125.29.101. Cloud DNS is programmable.
  You can easily publish and manage millions of DNS zones and records using our simple
  user interface, command-line interface or API.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Project
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/project/master/_listings/google-cloud-dns/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud DNS API Get Project
  x-api-slug: google-cloud-dns-api
  description: Fetch the representation of an existing Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}
  tags: Project
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/project/master/_listings/google-cloud-dns/project-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/project/master/_listings/google-cloud-dns/project-get-openapi.md
- name: Google Cloud DNS API
  x-api-slug: google-cloud-dns-api
  description: Google Cloud DNS is a scalable, reliable and managed authoritative
    Domain Name System (DNS) service running on the same infrastructure as Google.
    It has low latency, high availability and is a cost-effective way to make your
    applications and services available to your users. Cloud DNS translates requests
    for domain names like www.google.com into IP addresses like 74.125.29.101. Cloud
    DNS is programmable. You can easily publish and manage millions of DNS zones and
    records using our simple user interface, command-line interface or API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects
  tags: Project
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/project/master/_listings/google-cloud-dns/openapi.md
x-common:
- type: x-documentation
  url: https://cloud.google.com/dns/docs/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/cloud-dns-discuss
- type: x-getting-started
  url: https://cloud.google.com/dns/quickstart
- type: x-guides
  url: https://cloud.google.com/dns/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/dns/pricing
- type: x-rate-limits
  url: https://cloud.google.com/dns/quota
- type: x-service-level-agreements
  url: https://cloud.google.com/dns/sla
- type: x-website
  url: https://cloud.google.com/dns/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---