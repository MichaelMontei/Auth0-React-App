# Auth0-React-App
Lets make a Login App with Auth0 authentication (hooks, props and states

In this repository I wanna make an Authentication app with React.

For the preparation we need to do some steps :

### Step 1
- We need to make an account on https://auth0.com/ and sign up here, It will make a tenant for us we can use.
- Afterwards we go to applications and let's create new Application.
- Here we go to the settings and we need to change the Application URIs to be http://localhost:3000 
 
 We do this for Allowed Callback URLs, Allowed Logout URLs and the Allowed Web Origins.

### Step 2
We gonna need to make a GLOBAL .ENV file in our application with two parameters:
-  REACT_APP_AUTH0_Domain = Domain(auth0) in ur basic information
-  REACT_APP_AUTH0_CLIENT_ID = Client ID(auth0) in ur basic information

### Step 3
We need to install the auth0 npm package -> npm i @auth0/auth0-react

Now we are ready to actually start on the application itself!



