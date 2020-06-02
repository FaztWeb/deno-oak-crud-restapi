# Deno REST API
A simple CRUD REST API example using Deno and Oak

## Run Locally
```
deno run --allow-net server.ts
```

## Run by URL
```
deno run --allow-net https://raw.githubusercontent.com/FaztWeb/deno-oak-crud-restapi/master/server.ts
```

# Endpoints

Get All users
```
GET      /users
```

Get a single User by Id
```
GET      /users/:id
```

Create a new User
```
POST     /products
```

Update an existing User by Id
```
PUT      /users/:id
```

Delete an existing User by Id
```
DELETE   /users/:id
```