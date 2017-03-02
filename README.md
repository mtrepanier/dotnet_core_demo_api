# Welcome to Dotnet Core Demo API

Small ToDo Web API using in memory DB context

## To make it work:

* Have all the dotnet core prerequist (https://www.microsoft.com/net/core)
* Clone this repository
* Run `dotnet restore` to install all NuGet package
* Launch the app `dotner run`

## Sample of API call (restful api)

* Get all todo
    * get: `/api/todo`
* Get on todo
    * get: `/api/todo/{id}`
* Create a todo
    * post: `/api/todo` with json payload : ```
        {
            "name":"Drink Rhum",
            "isCompleted":false
        }```
* Update a todo
    * put: `/api/todo/{id}` with json payload : ```
        {
            "name":"Drink Rhum",
            "isCompleted":true
        }```
* Delete a todo
    * delete: `/api/todo/{id}`
