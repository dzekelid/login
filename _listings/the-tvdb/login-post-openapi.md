---
swagger: "2.0"
x-collection-name: The TVDB
x-complete: 0
info:
  title: The TVDB Post Login
  description: Returns a session token to be included in the rest of the requests.
    Note that API key authentication is required for all subsequent requests and user
    auth is required for routes in the `User` section
  version: 2.1.2
host: api-dev.thetvdb.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /login:
    post:
      summary: Post Login
      description: Returns a session token to be included in the rest of the requests.
        Note that API key authentication is required for all subsequent requests and
        user auth is required for routes in the `User` section
      operationId: login.post
      x-api-path-slug: login-post
      parameters:
      - in: body
        name: Authentication string
        description: JSON string containing your authentication details
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Television
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