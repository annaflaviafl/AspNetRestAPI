## Login
```
POST {{host}}/auth/login
```

#### Login Request
```json
{
    "email": "annaflavialf@email.com",
    "password": "Anna1232!"
}
```

```js
200 OK
```

#### Login Response

```json
{
    "id": "d89c2d9a-eb3e-4075-95ff-b920b55aa104",
    "firstName": "Anna Flávia",
    "lastName": "Lopes",
    "email": "annaflavialf@email.com",
    "token": "eyJhb..hbbQ"
}
````

