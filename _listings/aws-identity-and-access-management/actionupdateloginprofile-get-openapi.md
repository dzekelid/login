---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API Update Login Profile
  version: 1.0.0
  description: Changes the password for the specified IAM user.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateLoginProfile:
    get:
      summary: Create Login Profile
      description: |-
        Creates a password for the specified user, giving the user the ability to access AWS
              services through the AWS Management Console.
      operationId: createLoginProfile
      x-api-path-slug: actioncreateloginprofile-get
      parameters:
      - in: query
        name: Password
        description: The new password for the user
        type: string
      - in: query
        name: PasswordResetRequired
        description: Specifies whether the user is required to set a new password
          on next sign-in
        type: string
      - in: query
        name: UserName
        description: The name of the IAM user to create a password for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Login Profiles
  /?Action=DeleteLoginProfile:
    get:
      summary: Delete Login Profile
      description: |-
        Deletes the password for the specified IAM user, which terminates the user's ability
              to access AWS services through the AWS Management Console.
      operationId: deleteLoginProfile
      x-api-path-slug: actiondeleteloginprofile-get
      parameters:
      - in: query
        name: UserName
        description: The name of the user whose password you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Login Profiles
  /?Action=GetLoginProfile:
    get:
      summary: Get Login Profile
      description: Retrieves the user name and password-creation date for the specified
        IAM user.
      operationId: getLoginProfile
      x-api-path-slug: actiongetloginprofile-get
      parameters:
      - in: query
        name: UserName
        description: The name of the user whose login profile you want to retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Login Profiles
  /?Action=UpdateLoginProfile:
    get:
      summary: Update Login Profile
      description: Changes the password for the specified IAM user.
      operationId: updateLoginProfile
      x-api-path-slug: actionupdateloginprofile-get
      parameters:
      - in: query
        name: Password
        description: The new password for the specified IAM user
        type: string
      - in: query
        name: PasswordResetRequired
        description: Allows this new password to be used only once by requiring the
          specified IAM user to      set a new password on next sign-in
        type: string
      - in: query
        name: UserName
        description: The name of the user whose password you want to update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Login Profiles
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