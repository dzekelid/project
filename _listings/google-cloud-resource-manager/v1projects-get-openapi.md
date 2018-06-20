---
swagger: "2.0"
x-collection-name: Google Cloud Resource Manager
x-complete: 0
info:
  title: Google Cloud Resource Manager API List Projects
  description: |-
    Lists Projects that are visible to the user and satisfy the
    specified filter. This method returns Projects in an unspecified order.
    New Projects do not necessarily appear at the end of the list.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: cloudresourcemanager.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/projects:
    get:
      summary: List Projects
      description: |-
        Lists Projects that are visible to the user and satisfy the
        specified filter. This method returns Projects in an unspecified order.
        New Projects do not necessarily appear at the end of the list.
      operationId: cloudresourcemanager.projects.list
      x-api-path-slug: v1projects-get
      parameters:
      - in: query
        name: filter
        description: An expression for filtering the results of the request
      - in: query
        name: pageSize
        description: The maximum number of Projects to return in the response
      - in: query
        name: pageToken
        description: A pagination token returned from a previous call to ListProjectsthat
          indicates from where listing should continue
      responses:
        200:
          description: OK
      tags:
      - Project
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---