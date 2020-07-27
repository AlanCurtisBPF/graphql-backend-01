Graphql with Fake DB
---
## Install node modules

``` npm i ```

## Start Fake DB

``` npm run json:server ```

## Start Server

``` npm run dev:server ```

## Now you can use Graphiql interface
go to `http://localhost:4000/graphql`
make request:
``` 
{
customers
{
  name,
  age
}
}
```
or 
```
{
  customer(id: "4"){
    name,
    id,
    email,
  }
}
```
