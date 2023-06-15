# API-Testing
 <h2>Base URL</h2>
 https://reqres.in
 <h2>Authentication</h2>
 This API does not require authentication or an API key to access.
 <h2>Endpoints</h2>
 <h3>1. POST/api/users</h3>
 Description
 
 Create a new user

 Parameter
 
 | Name | Type  |
 | ---- | ----  |
 | name | string|
 | job  | string|
 
Example Request
 ``` bash

POST/api/users
{
    "name": "Fajar",
    "job": "SQA"
}
```
<h3>2. PUT/api/users/{{id}}</h3>
 Description
 
 Update the user based on the ID

 Parameter
 
 | Name | Type  |
 | ---- | ----  |
 | name | string|
 | job  | string|
 | id   | int   |

 Example Request
 ``` bash

PUT/api/users/{{id}}
{
    "name": "Ari",
    "job": "SQA"
}
```
<h3>3. DELETE/api/users/{{id}}</h3>
 Description
 
 Delete the user based on the ID

 Parameter
 
 | Name | Type  |
 | ---- | ----  |
 | id   | int   |

 Example Request
 ``` bash

DELETE/api/users/{{id}}
```
 
 
 
