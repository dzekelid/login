swagger: "2.0"
x-collection-name: Flickr
x-complete: 1
info:
  title: Flickr
  description: explore-upload-and-organize-photos-on-flickr
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