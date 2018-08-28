---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Users API Delete a user login
  description: Delete a user login.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /audit/authentication/logins/{login_id}:
    get:
      summary: Query by login.
      description: Query by login..
      operationId: query-by-login
      x-api-path-slug: auditauthenticationloginslogin-id-get
      parameters:
      - in: query
        name: end_time
        description: The end of the time range from which you want events
      - in: query
        name: start_time
        description: The beginning of the time range from which you want events
      responses:
        200:
          description: OK
      tags:
      - Audit
      - Authentication
      - Logins
      - Login
      - Id
  /users/{user_id}/logins:
    get:
      summary: List user logins
      description: List user logins.
      operationId: list-user-logins
      x-api-path-slug: usersuser-idlogins-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Logins
  /users/{user_id}/logins/id:
    delete:
      summary: Delete a user login
      description: Delete a user login.
      operationId: delete-a-user-login
      x-api-path-slug: usersuser-idloginsid-delete
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Logins
      - Id
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