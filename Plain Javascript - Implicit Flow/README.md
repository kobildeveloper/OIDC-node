# mIDentityBox - Implicit Flow using Plain Javascript

This repo contains plain javascript example app that demonstrate the various OpenId Connect's Implicit flow.

## Instructions
1. Initially clone this repository
2. Navigate to `Plain Javascript - Implicit Flow` folder in terminal
3. You can configure your OIDC related information in ```./index.html``` file
4. Make sure you replace `your-midentity-box-oidc-tenant-id` with your TenantID and `your-midentity-box-oidc-app-client-id` with your ClientID  when you created your OpenId Connect app via the mIDentity Box portal
5. Change `{partnerid}.{hostname}` to match the sub-domain by mIDentity Box portal
6. Need to install [http-server](https://www.npmjs.com/package/http-server), to serve the `index.html` file as localhost
7. RUN `npm i http-server -g` to install `http-server` as a global package
8. Once `http-server` is installed, RUN `http-server` in the same terminal, pointing to the root folder which has `index.html` file
9. You will receive a localhost URL, open that specific URL in the browser to view your initial screen

**Note:** Check with mIDentity Box administrator to enable Implicit Flow

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
2. You will be redirected to "mIDentityBox" user authentication screen
3. Type username, then click "Continue to login"
4. You will receive a transaction in your mIDentityBox app
5. You can able to "Accept/Decline" the transaction request
6. By accepting the transaction from mobile app, you can able to authorize your login

### Mobile App
1. [Android app](https://play.google.com/store/apps/details?id=com.kobil.mIdentity.box)
2. [iOS App](https://apps.apple.com/us/app/midentity-box/id1534159545)


If you don't have a mIDentity Box account [you can sign up here](https://midentitybox.com/selfenrollment).
