{
  "info": {
    "name": "Viddler  API Logins Add",
    "_postman_id": "208cd0c2-a2e1-458c-9b23-dd35cc8bf01a",
    "description": "Adds a new login to user account when the main account has multi-user sign-on enabled. You must have this feature enabled for your account. Please call us at 1-888-444-1119 to enable for you account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Viddler",
      "item": [
        {
          "id": "e369fe47-9a05-4698-8d1b-c401e44f8fb2",
          "name": "api-echo",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.api.echo?message=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This method is used for testing purposes only. Simply call this method to make sure the API is responding fine."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "28b7e335-645f-4f57-99f9-04af676eb1df"
            }
          ]
        },
        {
          "id": "70fd8982-2c34-4149-8b65-40fa6d56bf05",
          "name": "encoding-cancel",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.encoding.cancel?file_id=%7B%7D&sessionid=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Cancel encoding a specific video file."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9322e51-a84a-4135-a33e-17b5e07761cc"
            }
          ]
        },
        {
          "id": "9e5e4d07-d832-48eb-b5c7-34ca210cc425",
          "name": "encoding-getsettings",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.encoding.getSettings?sessionid=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the current encoding options for an account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2afe814-5b95-4226-aa86-d88c24b54983"
            }
          ]
        },
        {
          "id": "f389d8dd-5f68-4484-896b-347e76bfbe5c",
          "name": "encoding-getstatus2",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.encoding.getStatus2?sessionid=%7B%7D&video_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This method is the same as viddler.encoding.getStatus except that it groups files better for users to easily find what they are looking for. We could not easily update the previous method without causing complications with external applications."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0fd1b2d-2c9d-4338-b8cd-1596711c9e05"
            }
          ]
        },
        {
          "id": "9226832e-5832-4452-b7cc-caa5790546aa",
          "name": "logins-add",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.logins.add?analytics_permissions=%7B%7D&api_access_permissions=%7B%7D&api_settings_permissions=%7B%7D&billing_settings_permissions=%7B%7D&branding_settings_permissions=%7B%7D&email=%7B%7D&encoding_settings_permissions=%7B%7D&interaction_settings_permissions=%7B%7D&invoices_permissions=%7B%7D&itunes_settings_permissions=%7B%7D&login=%7B%7D&logins_permissions=%7B%7D&name=%7B%7D&password=%7B%7D&player_settings_permissions=%7B%7D&playlists_permissions=%7B%7D&playlist_ids=%7B%7D&privacy_settings_permissions=%7B%7D&profile_permissions=%7B%7D&recorder_permissions=%7B%7D&sessionid=%7B%7D&subaccounts_permissions=%7B%7D&support_permissions=%7B%7D&videos_permissions=%7B%7D&vidgets_permissions=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a new login to user account when the main account has multi-user sign-on enabled. You must have this feature enabled for your account. Please call us at 1-888-444-1119 to enable for you account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6c65403-5041-4672-ac1f-885f7c8c3ae5"
            }
          ]
        }
      ]
    }
  ]
}