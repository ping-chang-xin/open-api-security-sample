# Running Steps

1. open project using Intellij IDEA
2. run project
3. open postman
4. post <http://localhost:8080/api/v1/auth/signup> with below json, email/password can be whatever you want

```json
{
    "email": "admin@github.com",
    "password": "123456"
}
```

5. copy the token from the response
6. post <http://localhost:8080/api/v1/resource> with Authorization Type Bearer Token
