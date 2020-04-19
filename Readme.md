# WebAPI Experiments

From https://www.linkedin.com/learning/learning-rest-apis/

Use Rest Client Extension

## Request
### GET
- 200
- 404
### POST (Insert New Collection)
- 201 Created
- 401 Unauth
- 409 Conflict
- 404
### PUT (Update)
- 200
- 401
- 404
- 405 Method not Allowed
### PATCH (Small Update, should give what to update)
- 200
- 401
- 404
- 405
### DELETE
- 200
- 401
- 404

Aditionally

### OPTIONS (methods allowed)
- 200

### HEAD (just response headers)
- 200
- 404


## Response

Most Import is Content-Type like "application/json; charset=UTF-8"


## Authorization

(not used online)
Authorization: Basic user pwd 