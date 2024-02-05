# Assessment_sdt
Assessment_sdt_test robertto Sanly

<!-- GETTING STARTED -->
## Getting Started
Download and run app.js in the root folder.
* node
  ```sh
  node app.js
  
## API
use http://localhost:3001/ or http://ip-address:3001/ as base url

* Create User
  
    | key          | Format/type         |  Example Value          | Description                   |
    | -----------  | ------------------- | ------------------------|------------------------------ |
    | `first`      | text                | momo                    | First Name                    |
    | `last`       | text                | mimi                    | Last Name                     |
    | `email`      | email               | momo@mimi.com           | email user                    |
    | `dob`        | YYYY-MM-DD          | 2013-02-03              | Date of Birth                 |
    | `timezone`   | +/-HH:SS            | +07:00                  | Offset timezone user          |

      ```sh
        method : POST
        http://localhost:3000/user/
        body : x-www-form-urlencoded

  * Delete User
  
  | key          | Format/type         |  Example Value          | Description                   |
  | -----------  | ------------------- | ------------------------|------------------------------ |
  | `id`         | int                 | 17                      | delete user by id             |  
      ```sh
        method : DELETE
        http://localhost:3000/user/
        body : x-www-form-urlencoded
  
  * Edit User 
     ```sh
      method : PUT
      http://localhost:3000/user/
      body : x-www-form-urlencoded
  | key          | Format/type         |  Example Value          | Description                   |
  | -----------  | ------------------- | ------------------------|------------------------------ |
  | `id`         | int                 | 14                      | Id user want to edit          |
  | `first`      | text                | momo                    | First Name                    |
  | `last`       | text                | mimi                    | Last Name                     |
  | `email`      | email               | momo@mimi.com           | email user                    |
  | `dob`        | YYYY-MM-DD          | 2013-02-03              | Date of Birth                 |
  | `timezone`   | +/-HH:SS            | +07:00                  | Offset timezone user          |


     
