# mIDentityOne - Implicit Flow using Plain Javascript

This repo contains plain javascript example app that demonstrate the various OpenId Connect's Implicit flow.

## Instructions
1. Initially clone this repository
2. Navigate to `Plain Javascript - Implicit Flow` folder in terminal
3. Need to install [http-server](https://www.npmjs.com/package/http-server), to serve the `index.html` file as localhost
4. RUN `npm i http-server -g` to install `http-server` as a global package
5. Once `http-server` is installed, RUN `http-server` in the same terminal, pointing to the root folder which has `index.html` file
6. You will receive a localhost URL, open that specific URL in the browser to view your initial screen

### Example
```
Starting up http-server, serving ./
Available on:
  http://127.0.0.1:8081
  http://192.168.225.192:8081
Hit CTRL-C to stop the server
```

## Approach to work with the implicit flow
1. Click on "login" button
2. You will be redirected to "mIDentityOne" user authentication screen
3. Type username, then click "Continue to login"
4. You will receive a transaction in your mIDentityOne app
5. You can able to "Accept/Decline" the transaction request
6. By accepting the transaction from mobile app, you can able to authorize your login

### Mobile App
1. [Android app](https://play.google.com/store/apps/details?id=com.kobil.mIdentity)
2. [iOS App](https://apps.apple.com/us/app/midentity/id1474814314)


If you don't have a mIDentity One account [you can sign up here](https://midentity.one/selfenrollment).