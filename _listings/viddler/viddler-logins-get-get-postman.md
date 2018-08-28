{
  "info": {
    "name": "Viddler  API Logins Get",
    "_postman_id": "98c2f7a5-aa34-41bc-a1e5-6f07d8d0cf1e",
    "description": "Return the current permissions for a specific user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Viddler",
      "item": [
        {
          "id": "c66704de-cf3a-4011-a467-b49033092b5a",
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
              "id": "6dd5a950-3cab-4473-bfb9-3e992e7501cc"
            }
          ]
        },
        {
          "id": "a5539e52-a8b4-4046-a66f-2c9090a0064e",
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
              "id": "81a18afb-b00e-4daf-939c-ae3c49a460d1"
            }
          ]
        },
        {
          "id": "d9719bc2-2186-4b32-b56e-e499be6b48b4",
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
              "id": "145d6b69-db1b-491c-b0a1-2bb45f3288bd"
            }
          ]
        },
        {
          "id": "85aa2534-aaa9-4d3d-85cc-c73a01284950",
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
              "id": "0cc2c3ec-07d7-4d0f-a3c4-25896a2bee70"
            }
          ]
        },
        {
          "id": "c18a221e-d23e-493d-8398-ab9853d43fc8",
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
              "id": "6b345b26-7f42-4627-bbd4-c63a285081d1"
            }
          ]
        },
        {
          "id": "f8278bb8-f2fd-497d-b467-4349d8bba4e5",
          "name": "logins-get",
          "request": {
            "url": "http://api.viddler.com/api/v2/viddler.logins.get?login=%7B%7D&sessionid=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return the current permissions for a specific user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e49147e-abb7-408a-87cd-e5ab13ac946d"
            }
          ]
        }
      ]
    }
  ]
}