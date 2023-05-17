
# Reqres.in-Rest-Api-Testing


## Documentation

[Documentation](https://linktodocumentation)


## How to run this project

- Clone this project
- Open with Postman / Command Shell
- Run Command:

```cmd
 newman run Reqres.in-Api.postman_collection.json -e Reqres.in-Api.postman_environment.json
```
- Command for report
```cmd
  newman run Reqres.in-Api.postman_collection.json -e Reqres.in-Api.postman_environment.json -r cli,htmlextra
```


## Technology Used
- Postman
- Newman

## Prerequisite
- Jdk
- Node Js
- Newman
- Html Report Library
## Test cases List:
1. ### Create User
  - Create Data Sets Using the Dynamic Random Variables.

  - In the test case    you need to validate the following field values:
    - id 
   
    - First Name

    - Last Name

    - Email

    - Avatar

2. ### Update User
* In the test case you need to validate the following field values:

    -  Status Code
    - First Name
    - Last Name
    - Avatar
    
3. ###  Partial Update User's (email)
* In the test case you need to validate the following field values:

    - Status Code
    - Email
   

4. ### Get the User's Full Details

In the test case you need to validate the following field values:
- Status code


5. ### Delete Specific Student
In the test case you need to validate the following field values:

- Status code

6. ### Registration
In the test  case you need to validate following field vaues:
- Status code

7. ### Login
In the test  case you need to validate following field vaues:
- Status code
- Token 
## Newman Summery Report
![Report](https://github.com/Nahid-IIT/Reqres.in-Rest-Api-Testing/blob/main/images/1.PNG)
![report](https://github.com/Nahid-IIT/Reqres.in-Rest-Api-Testing/blob/main/images/2.PNG)
![report](https://github.com/Nahid-IIT/Reqres.in-Rest-Api-Testing/blob/main/images/3.PNG)
## Authors
[Nahidul Islam](https://github.com/Nahid-IIT)

