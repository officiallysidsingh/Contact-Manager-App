# My Contacts Backend

This is a backend project which lets users to login or register and store their contacts' name, email and phone number.

## ENDPOINTS

This contains two sets of endpoints :-

- User Endpoints - To Register, Login and See Current User Details
- Contacts - To Create, Get, Update and Delete Contacts of The Logged In User.

### User Endpoints

- /api/users/register - POST - Public Route - To register a new user
- /api/users/login - POST - Public Route - To login a user
- /api/users/current - GET - Private Route - To get details of the user logged in

### Contact Endpoints - ALL ARE PRIVATE ROUTES

- /api/contacts - GET - To get all contacts
- /api/contacts - POST - To create a new contact

- /api/contact/:id - GET - To get contact with id as given
- /api/contact/:id - PUT - To update a contact with id as given
- /api/contact/:id - DELETE - To delete a contact with id as given

## TOOLS USED

- Express
- Node
- JWT for Token Authentication And Validation
- Bcrypt for Password Hashing

## SERVER CONTROL FLOW

![Server-Control-Flow](https://github.com/officiallysidsingh/Contact-Manager-App/assets/55332990/60195bd4-b87f-43a7-b6ef-bcce747a9e04)
