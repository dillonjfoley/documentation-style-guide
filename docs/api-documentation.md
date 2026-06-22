# API documentation rules

## Purpose

API documentation should help developers understand, test, and troubleshoot an API quickly.

## Required sections

Each endpoint should include:

- Method
- Endpoint path
- Description
- Authentication requirements
- Path parameters
- Query parameters
- Request body
- Response body
- Status codes
- Error responses
- Example request
- Example response

## Endpoint format

```md
## Get a project

`GET /v1/projects/{project_id}`

Returns information about a project.
