# Assignment 4

### Name:Abrayev Daniyal  
### Group: SE-2432


# Project description
With blood and tears I made this assignment. Sometimes I think I regret being IT student.
This assignment introduces Role-Based
Access Control (RBAC) using password hashing and JWT (JSON Web Tokens) to protect
your resources.


## Requirements
This project uses environment variables for security. You must create a .env file with MongoDB connections string locally.

Example:
`"MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/name"`

## How to install dependencies

`npm install`  

## How to run the server

`npm start` 

# 1. Refined Project Architecture (MVC Pattern)
![Server is running](https://github.com/helpicantchoose/helpicantchoose-web_technologies_2_assignment_4/blob/main/imgages/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-02-01%20014914.png?raw=true)

# 2. My objects
![Server is running](https://github.com/helpicantchoose/helpicantchoose-web_technologies_2_assignment_4/blob/main/imgages/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-02-01%20015150.png?raw=true)

# 3. Authentication & Role-Based Access Control (RBAC)
![Server is running](https://github.com/helpicantchoose/helpicantchoose-web_technologies_2_assignment_4/blob/main/imgages/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-02-01%20015225.png?raw=true)


## Example 
Good request
![Server is running](https://github.com/helpicantchoose/helpicantchoose-web_technologies_2_assignment_4/blob/main/imgages/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-02-01%20015510.png?raw=true)

Unauthorized
![Server is running](https://github.com/helpicantchoose/helpicantchoose-web_technologies_2_assignment_4/blob/main/imgages/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-02-01%20015831.png?raw=true)

Main page example
![Server is running](https://github.com/helpicantchoose/helpicantchoose-web_technologies_2_assignment_4/blob/main/imgages/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-02-01%20013334.png?raw=true)
