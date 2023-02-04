# JWT-Flask-authentication
## Jason Web Tokens(JWT)
``` 
JSON Web Tokens is a secure and compact way to transmit data between two parties with the help of JSON objects 
  JSON web token consists of three parts
   Payload
   Header
   Signature
  ```
## STEPS
### Required packages 
```
Flask-RESTful
PyJWT
Flask-SQLAlchemy
```
## Generating secret key
### By commands
``` 
  1. import os
     os.urandom(12)
  2. import uuid
     uuid.uuid4().hex
  3. import secrets
     secrets.token_urlsafe(12)
 ```
 
 ####  The value assigned to the config variable ‘SECRET KEY’ can be auto-generated using a python libraries
 ### run the main program
 ``` 
 python app.py
 ```
 ## Demo Link
 ``` https://drive.google.com/file/d/1p4SHm6w5ZhiwdOx9eb8xw5-87RA540EV/view?usp=sharing
  ```
