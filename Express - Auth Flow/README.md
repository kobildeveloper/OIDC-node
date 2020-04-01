# mIDentity One OpenId Connect - Authorization Flow using Express Framework

## About
This repo contains express example app that demonstrate the various OpenId Connect's Authorization flows. This is a Node.js Express app that uses Keycloak to protect the /authorizedRoute route, Login and user setup are controlled by keycloak. The default route / is unprotected. The /logout route clears the keycloak session.

## Instructions
1. Initially clone this repository
2. Navigate to `Express - Auth Flow` folder
3. RUN `npm install`
4. After installation of NPM packages, RUN `npm run start`
5. By default this node app will run port `3000`
6. Finally go to browser and launch `http://localhost:3000`

## Approach to work with the authorization flow

Here we had followed two types of routes
```
http://localhost:3000 - Unauthorized Route
http://localhost:3000/authorizedRoute - Authorized/Protected Route

```

### Once you navigate to the initial route follow below mentioned instructions
1. Click on "login" button
2. You will be redirected to "mIDentityOne" user authentication screen
3. Type username, then click "Continue to login"
4. You will receive a transaction in your mIDentityOne app
5. You can able to "Accept/Decline" the transaction request
6. Once you "Accept" the transaction you will redirected to `Authorized/Protected Route`
7. So you will be in `Authorized/Protected Route`, if you need to logout of your session click "logout" button

### Mobile App
1. [Android app](https://play.google.com/store/apps/details?id=com.kobil.mIdentity)
2. [iOS App](https://apps.apple.com/us/app/midentity/id1474814314)


If you don't have a mIDentity One account [you can sign up here](https://midentity.one/selfenrollment).