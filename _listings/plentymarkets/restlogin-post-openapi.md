---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Login
  description: Logs in to plentymarkets with your back end user credentials. The login
    call returns a JSON object that contains information, such as the access token
    and the refresh token.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/account/login:
    post:
      summary: Login
      description: Logs in to the online store with front end user credentials. The
        login call returns a JSON object that contains information, such as the access
        token and the refresh token.
      operationId: postRestAccountLogin
      x-api-path-slug: restaccountlogin-post
      parameters:
      - in: body
        name: /rest/account/login
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Login
  /rest/accounts/contacts/{contactId}/access_data/login_url:
    get:
      summary: Get the login URL
      description: Gets the URL to login as the given contact. The ID of the contact
        must be specified.
      operationId: getRestAccountsContactsContactAccessDataLoginUrl
      x-api-path-slug: restaccountscontactscontactidaccess-datalogin-url-get
      parameters:
      - in: path
        name: contactId
      responses:
        200:
          description: OK
      tags:
      - Login
      - URL
  /rest/login:
    post:
      summary: Login
      description: Logs in to plentymarkets with your back end user credentials. The
        login call returns a JSON object that contains information, such as the access
        token and the refresh token.
      operationId: postRestLogin
      x-api-path-slug: restlogin-post
      parameters:
      - in: body
        name: /rest/login
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
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