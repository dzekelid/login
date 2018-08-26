---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Adminuser Action Login
  description: Get an admin session using admin email and password (Used for login
    to the KMC application)
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/adminuser/action/login:
    get:
      summary: Get Service Adminuser Action Login
      description: Get an admin session using admin email and password (Used for login
        to the KMC application)
      operationId: adminUser.login
      x-api-path-slug: serviceadminuseractionlogin-get
      parameters:
      - in: query
        name: email
      - in: query
        name: No Name
      - in: query
        name: partnerId
      - in: query
        name: password
      responses:
        200:
          description: OK
      tags:
      - Service
      - Adminuser
      - Action
      - Login
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