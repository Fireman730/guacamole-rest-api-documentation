<!-- omit in toc -->
# History

History gives you get history log.

<!-- omit in toc -->
# Table of Contents

- [List Connection History](#list-connection-history)
    - [Headers](#headers)
    - [Path Parameters](#path-parameters)
    - [Query Parameters](#query-parameters)
    - [Request Body](#request-body)
  - [Response](#response)
    - [Status Code](#status-code)
    - [Response Body](#response-body)
- [List Users History](#list-users-history)
    - [Headers](#headers-1)
    - [Path Parameters](#path-parameters-1)
    - [Query Parameters](#query-parameters-1)
    - [Request Body](#request-body-1)
  - [Response](#response-1)
    - [Status Code](#status-code-1)
    - [Response Body](#response-body-1)

## List Connection History

List connection history.

<!-- omit in toc -->
### GET /api/session/data/{{data_source}}/history/connections

#### Headers

None.

#### Path Parameters

- data_source (string, required) - Data source

#### Query Parameters

- token (string, required) - Auth Token
- contains (string, optional) - Contains
- order (string, optional) - Property name to order

#### Request Body

None.

### Response

#### Status Code

- 200 - OK

#### Response Body

**@TODO**

---

## List Users History

List user history.

<!-- omit in toc -->
### GET /api/session/data/{{data_source}}/history/users

#### Headers

None.

#### Path Parameters

- data_source (string, required) - Data source

#### Query Parameters

- token (string, required) - Auth Token
- order (string, optional) - Property name to order

#### Request Body

None.

### Response

#### Status Code

- 200 - OK

#### Response Body

**@TODO**

---

[Back to Top](#history)
