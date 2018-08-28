swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
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