swagger: "2.0"
x-collection-name: 123FormBuilder
x-complete: 1
info:
  title: ""
  version: 1.0.0
host: api.123contactform.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /token:
    post:
      summary: User login
      description: "Allows you to authenticate users. \n\nRequired parameters:\n-
        username OR email\n- password OR passhash"
      operationId: allows-you-to-authenticate-users-required-parameters-username-or-email-password-or-passhash
      x-api-path-slug: token-post
      parameters:
      - in: query
        name: email
      - in: query
        name: passhash
        description: MD5 password
      - in: query
        name: password
        description: Plain text password
      - in: query
        name: username
      responses:
        200:
          description: OK
      tags:
      - User
      - Login