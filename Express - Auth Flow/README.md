# mIDentityBox - Authorization Flow using Express Framework

## About
This repo contains express example app that demonstrate the various OpenId Connect's Authorization flows. This is a Node.js Express app that uses Keycloak to protect the /authorizedRoute route, Login and user setup are controlled by keycloak. The default route / is unprotected. The /logout route clears the keycloak session.

## Instructions
1. Initially clone this repository
2. Navigate to `Express - Auth Flow` folder
3. You can configure your OIDC related information in ```./keycloak.json``` file
4. Make sure you replace `your-midentity-box-oidc-tenant-id` with your TenantID and `your-midentity-box-oidc-app-client-id` with your ClientID  when you created your OpenId Connect app via the mIDentity Box portal.
5. Change `{partnerid}.{hostname}` to match the sub-domain by mIDentity Box portal.
6. RUN `npm install`
7. After installation of NPM packages, RUN `npm run start`
8. By default this node app will run port `3000`
9. Finally go to browser and launch `http://localhost:3000`

## Approach to work with the authorization flow

Here we had followed two types of routes
```
http://localhost:3000 - Unauthorized Route
http://localhost:3000/authorizedRoute - Authorized/Protected Route

```

### Once you navigate to the initial route follow below mentioned instructions
1. Click on "login" button
2. You will be redirected to "mIDentityBox" user authentication screen
3. Type username, then click "Continue to login"
4. You will receive a transaction in your mIDentityBox app
5. You can able to "Accept/Decline" the transaction request
6. Once you "Accept" the transaction you will redirected to `Authorized/Protected Route`
7. So you will be in `Authorized/Protected Route`, if you need to logout of your session click "logout" button

### Mobile App
1. [Android app](https://play.google.com/store/apps/details?id=com.kobil.mIdentity.box)
2. [iOS App](https://apps.apple.com/us/app/midentity-box/id1534159545)


If you don't have a mIDentity Box account [you can sign up here](https://midentitybox.com/selfenrollment).
