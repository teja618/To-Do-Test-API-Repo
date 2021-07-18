# To-Do-Test-API-Repo
This sample test API is used for React UI starter project.

Requirements: MySQl DB Server running on Port: 3306. [https://dev.mysql.com/downloads/file/?id=463209]


Sample Request:

PUT: http://localhost:8080/api/v1/todo/updateitem/1110

{
    "todoTitle":"Buy a book update",
    "todoDescription":"Buy a book online updated",
    "isComplete":false,
    "todoDate":"18-08-2021"
}  

Sample Response:

{
    "message": "Item with the following title Buy a book update updated",
    "code": 200,
    "httpStatus": "OK"
}
