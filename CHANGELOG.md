Changes
=======

3.2.0
------------------

Authentication API
- Better error handling.

Management API
- Better error handling.
- Fix inconsistence where UserBlocks required to be instantiated by the user.

3.1.4
------------------

Authentication API
- Improve handling of inconsistent API error responses.

3.1.3
------------------

Management API
- Added `upsert` parameter to `import_users` job.

3.1.2
------------------

Authentication API
- Added `refresh_token` method to get_token

3.1.0
------------------

Authentication API
- Added Logout Functionality

3.0.0 
------------------

Authentication API
- Added Support for API Authorization. `oauth/token` endpoint
  - Client Credentials Grant
  - Authorization Code Grant
  - Authorization Code PKCE Grant
  - Resource Owner Password Realm Grant
- Added Support for API Authorization. `authorize` endpoint
  - Authorization Code Grant

Management API v2
- Added Support for Guardian   
- Added Support to retrieve Logs
- Added Support to manage Resource Servers
- Added Support to manage Client Grants
- Added Suport to manage User blocks 
