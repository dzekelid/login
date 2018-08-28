---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr Test Login
  description: A testing method which checks if the caller is logged in then returns
    their username.
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.test.login:
    get:
      summary: Test Login
      description: A testing method which checks if the caller is logged in then returns
        their username.
      operationId: getRestMethodFlickr.test.login
      x-api-path-slug: restmethodflickr-test-login-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      responses:
        200:
          description: OK
      tags:
      - Test
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