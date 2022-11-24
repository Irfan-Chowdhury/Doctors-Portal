<div align='center'>

# Doctors Portal
</div>

<p align='left'><i>[Server Section]</i></p>

## `MODULE LIST`
- 74-1 Module overview and create server
- 74-2 Load available options from database
- 74-3 Simple Overview of React Query and load data
- 74-4 API naming convention and save Booking to database
- 74-5 (Interesting) Find available time slots for a day
- 74-6 (Recap) Load available time slots based on the date
- 74-7 (optional) Use mongodb aggregate project pipeline
- 74-8 Limit one booking per user per treatment per day
- 75-2 Display User specific Appointments using Data Table
- 75-3 Save Registered user information in the database
- 75-4 (Recap) Issue Simple JWT token
- 75-5 (Recap) Send JWT token to back end for verification
- 75-6 (Recap) Verify JWT Token and create custom hook
- 75-7 Load all users on the Dashboard page
- 75-8 Create Make admin API limit the feature based on admin level
- 75-9 (advanced) Prevent accessing Admin route via URL
- 76-1 Module Overview and Add a doctor admin route setup
- 76-2 Load services with data project and Add file type input
- 76-3 File Type image field and understand form data
- 76-8 Delete User VerifyAdmin middleware and load all doctors
- 76-9 Module Summary and modal correction
- 77-2 Create Payment route and get appointment by Id
- 77-6 Server side payment intents API to get client Secret from stripe
## `Setup Server`
- First create a folder and then run this command for generating <i>package.json</i>
    ```bash
    npm init -y
    ```
- Secondly run this
    ```bash
    npm i express cors dotenv mongodb
    ```


## `JWT Setup`
- install JWT token. visit https://github.com/auth0/node-jsonwebtoken
    ```bash
    npm install jsonwebtoken
    ```
- setup the code in index.js
    ```bash
    const jwt = require('jsonwebtoken');
    ```
- Then create random code, Firstly open terminal and type 
    ```bash
    node
    ```
    then type 
    ```bash
    require('crypto').randomBytes(64).toString('hex')
    ```
    then a string value will be shown, copy the text and setup in .env and copy the code below later <br>
    ```bash
    // var token = jwt.sign({ foo: 'bar' }, process.env.ACCESS_TOKEN_SECRET);
    const token = jwt.sign(user, process.env.ACCESS_TOKEN_SECRET,{expiresIn:'1h'});
    ```

- install stripe 
    ```bash
    npm install --save stripe
    ```

    follow the tutorial link:
    ```bash
    https://stripe.com/docs/payments/quickstart?lang=node&client=react
    ```


