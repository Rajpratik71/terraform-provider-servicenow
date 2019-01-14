## Name

`servicenow_oauth_entity`

## Arguments

* `name` - (Required) The display name of the OAuth App entity.
* `redirect_url` - (Optional) The OAuth app's endpoint to receive the authorization code.
* `access_token_lifespan` - (Optional) Number of seconds a newly created access token is good for.
* `refresh_token_lifespan` - (Optional) Number of seconds the refresh token is good for.
* `access`- (Optional) Whether this Script can be accessed from only this application scope or all application scopes. Values can be `package_private` or `public`. Default: `public`.
* `scope`- (Optional) Application ID that contains this resource. Changes forces a new resource. Default: `global`.

## Other attributes
* `id` - The unique identifier in the ServiceNow instance.
* `client_uuid` - The client unique identifier in the ServiceNow instance.
* `client_id` - The OAuth client id of the entity. Use this for OAuth handshakes.

## Notes

The client secret cannot be set.