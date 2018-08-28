---
name: LoginRadius
x-slug: loginradius
description: Simplify customer authentication and authorization to amplify your business
  with better understanding of your audience using our customer identity management
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1086-loginradius.jpg
x-kinRank: "8"
x-alexaRank: "60839"
tags: Login
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/login/master/_listings/loginradius/apis.md
specificationVersion: "0.14"
apis:
- name: Login Operations - Get the login mechanism to use when logging in.
  x-api-slug: login-get
  description: All login stages MUST be mentioned if there is >1 login type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1086-loginradius.jpg
  humanURL: http://www.loginradius.com/
  baseURL: :///login/http://localhost:8008/_matrix/client/api/v1
  tags: Login, Users, Authentication, Authentication, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Identities, Profiles, Service
    API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/login/master/_listings/loginradius/login-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/login/master/_listings/loginradius/login-get-openapi.md
- name: Login Operations - Submit a login action.
  x-api-slug: login-post
  description: If this is part of a multi-stage login, there MUST be a session key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1086-loginradius.jpg
  humanURL: http://www.loginradius.com/
  baseURL: :///login/http://localhost:8008/_matrix/client/api/v1
  tags: Login, Users, Authentication, Authentication, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Identities, Profiles, Service
    API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/login/master/_listings/loginradius/login-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://lloyds.bank.api.gallery.streamdata.io
- type: x-api-stack
  url: http://loginradius.stack.network
- type: x-base
  url: https://api.loginradius.com
- type: x-blog
  url: http://blog.loginradius.com
- type: x-blog-rss
  url: http://blog.loginradius.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/loginradius
- type: x-crunchbase
  url: http://www.crunchbase.com/company/loginradius
- type: x-developer
  url: http://www.loginradius.com/developers
- type: x-email
  url: privacy@loginradius.com
- type: x-email
  url: legal@loginradius.com
- type: x-email
  url: support@loginradius.com
- type: x-github
  url: https://github.com/LoginRadius
- type: x-pricing
  url: http://www.loginradius.com/pricing
- type: x-twitter
  url: https://twitter.com/LoginRadius
- type: x-website
  url: http://www.loginradius.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---