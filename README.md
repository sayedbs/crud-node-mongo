# Run Mongo DB
## make a collection mongodb://localhost:27017/crud


## API URLs

## Test API
get: http://localhost:8000/fetch -> "showing for test message"

## Add new user
post: http://localhost:8000/addUser

body JSON:
``{
    "name": "Md Abu Sayed",
    "email": "sayed021@gmail.com",
    "address": "Dhaka, Mohakhali"
} ``

## Get All users
get: http://localhost:8000/getUsers


## Update user
put: http://localhost:8000/update/:id like http://localhost:8000/update/17363849

body JSON:
``{
    "name": "test",
    "email": "test@gmail.com",
    "address": "[Dhaka, Mohakhali](https://www.linkedin.com/in/sayed021/)"
}``

## Delete User
put: http://localhost:8000/deleteUser/:id like [[http://localhost:8000/deleteUser/17363849]()](http://localhost:8000/api/user/deleteUser/67487ed44ee003f5bf7ebd3c)
