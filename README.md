# NodeJS-Task-App

# Technologies used:
1. `Express Js` - To create APIS
2. `MongoDB` - NoSQL Database

# Dependencies:
1. `@sendgrid/mail` - To send mails
2. `bcrypt` - To hash passwords
3. `jsonwebtoken` - To use as a key to identify objects
4. `mongoose` - To have user defined schema
5. `multer` - File upload
6. `sharp` - Resize, compress images
7. `validator` - To check for emails

# APIS Created:
Base API : https://rohandoshi21-task-app.herokuapp.com <br>
Users: <br>
* List All Users: `GET /users`
* Show Info: `GET /users/me`
* Update Info: `PATCH /users/me`
* Show Info: `GET /users/:id`
* Update Info: `PATCH /users/:id`
* Delete Info: `DELETE /users/:id`
* Logout Single: `POST /users/logout`
* Logout All Sessions: `POST /users/logoutAll`
* Upload Avatar: `POST /users/me/avatar`
* Show Avatar: `GET /users/:id/avatar`
* Delete Avatar: `DELETE /users/me/avatar`

Tasks:
* List All Tasks: `GET /tasks`
* Create Single Task: `POST /tasks`
* Show Single Task: `GET /tasks/:id`
* Update Single Task: `PATCH /tasks/:id`
* Delete Single Task: `DELETE /tasks/:id`
