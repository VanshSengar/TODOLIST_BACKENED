

1. Authentication

a. sign up - register
b. sign in - login 

a. Sign up/ Register
   1. Email
   2. Password
      --- abc@gmail.com --// Check if the mail is already registered, if yes, throw error;


b. Login/ Sign in
   1. Email -- // check if the email exists/registered, then 
   2. Password  -- // check Password is right or wrong, 



2.  -- We won't store pwd in plain text, we'll hash it; - external library bcrypt
      email and password, can we just store the email and password
      {
          email : vansh@gmail.com,
          password : vansh123;
      }


3.  Tokens - login/signup -> server will send the token; -- external library jsonwebtoken 
    token ->abcd ->  verifies -> we let the user in/perform



