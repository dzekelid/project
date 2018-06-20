---
swagger: "2.0"
x-collection-name: Firebase
x-complete: 0
info:
  title: Firebase Get Project Settings
  description: |-
    Gets the Tool Results settings for a project.

    May return any of the following canonical error codes:

    - PERMISSION_DENIED - if the user is not authorized to read from project
  version: 1.0.0
host: '{project_id].firebaseio.co}'
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{projectId}/settings:
    get:
      summary: Get Project Settings
      description: |-
        Gets the Tool Results settings for a project.

        May return any of the following canonical error codes:

        - PERMISSION_DENIED - if the user is not authorized to read from project
      operationId: toolresults.projects.getSettings
      x-api-path-slug: projectidsettings-get
      parameters:
      - in: path
        name: projectId
        description: A Project id
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