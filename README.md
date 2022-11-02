# Registration

```
  POST https://blog.kata.academy/api/users

  Request Headers
  Content-Type: application/json
  User-Agent: PostmanRuntime/7.29.2
  Accept: */*
  Postman-Token: f908a0a4-2fda-4430-8454-d685b324510d
  Host: blog.kata.academy
  Accept-Encoding: gzip, deflate, br
  Connection: keep-alive
  Content-Length: 111
  
  Response Headers
  Server: nginx/1.18.0 (Ubuntu)
  Date: Wed, 02 Nov 2022 13:20:22 GMT
  Content-Type: application/json; charset=utf-8
  Content-Length: 274
  Connection: keep-alive
  X-Powered-By: Express
  Access-Control-Allow-Origin: *
  Vary: X-HTTP-Method-Override
  ETag: W/"112-YawXVt57teW8C2x0idw0JA"
  
  Request Body
{
  "user": {
    "username": "alexxgleb",
    "email": "alexgleb@gmail.com",
    "password": "123"
  }
}

Response Body
{
    "user": {
        "username": "alexxgleb",
        "email": "alexgleb@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNjI2ZTk2OGRiNWU1MWIwMDRlOTg2YyIsInVzZXJuYW1lIjoiYWxleHhnbGViIiwiZXhwIjoxNjcyNTc5MjIyLCJpYXQiOjE2NjczOTUyMjJ9.d3KQc4L1neMscS9GL0PbQWVYWRW5_ezgVnuFU7UJxdA"
    }
}
```

# Login

```
POST https://blog.kata.academy/api/users/login

Request Headers
Content-Type: application/json
User-Agent: PostmanRuntime/7.29.2
Accept: */*
Postman-Token: b0d32d0c-2b6e-4da5-b486-406b7878f053
Host: blog.kata.academy
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
Content-Length: 81
Request Body
{
  "user": {
    "email": "alexgleb@gmail.com",
    "password": "123"
  }
}
Response Headers
Server: nginx/1.18.0 (Ubuntu)
Date: Wed, 02 Nov 2022 13:20:37 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 274
Connection: keep-alive
X-Powered-By: Express
Access-Control-Allow-Origin: *
Vary: X-HTTP-Method-Override
ETag: W/"112-KPJnFmYsK/bKlOhw37vVnQ"
Response Body
{
    "user": {
        "username": "alexxgleb",
        "email": "alexgleb@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNjI2ZTk2OGRiNWU1MWIwMDRlOTg2YyIsInVzZXJuYW1lIjoiYWxleHhnbGViIiwiZXhwIjoxNjcyNTc5MjIyLCJpYXQiOjE2NjczOTUyMjJ9.d3KQc4L1neMscS9GL0PbQWVYWRW5_ezgVnuFU7UJxdA"
    }
}
```

# Get user

```
GET https://blog.kata.academy/api/user

200
84 ms
Network
Request Headers
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNjI2ZTk2OGRiNWU1MWIwMDRlOTg2YyIsInVzZXJuYW1lIjoiYWxleHhnbGViIiwiZXhwIjoxNjcyNTc5MjM3LCJpYXQiOjE2NjczOTUyMzd9.TNcFz1lVOGA4EDfFtyeRLHEsSeo9B4v29NeHKHUL8AE
User-Agent: PostmanRuntime/7.29.2
Accept: */*
Postman-Token: 43959e7a-71a5-486b-a3ef-46ca31cd97bf
Host: blog.kata.academy
Accept-Encoding: gzip, deflate, br
Connection: keep-alive
Response Headers
Server: nginx/1.18.0 (Ubuntu)
Date: Wed, 02 Nov 2022 13:21:00 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 274
Connection: keep-alive
X-Powered-By: Express
Access-Control-Allow-Origin: *
ETag: W/"112-yHNYly0gfZvqxOJIy29q+g"
Response Body
{
    "user": {
        "username": "alexxgleb",
        "email": "alexgleb@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzNjI2ZTk2OGRiNWU1MWIwMDRlOTg2YyIsInVzZXJuYW1lIjoiYWxleHhnbGViIiwiZXhwIjoxNjcyNTc5MjYwLCJpYXQiOjE2NjczOTUyNjB9.SKgAy7bClN_y6cnFKvsjzGNpWDcvadpXAcJXFI896Q8"
    }
}
```
