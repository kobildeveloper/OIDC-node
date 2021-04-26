
# mIDentityBox OpenId Connect Samples

This repo contains plain javascript and express example apps that demonstrate the various OpenId Connect flows

1. [Authorization Flow using Express Framework](https://github.com/kobildeveloper/OIDC-node/tree/master/Express%20-%20Auth%20Flow)
2. [Implicit Flow using Plain Javascript](https://github.com/kobildeveloper/OIDC-node/tree/master/Plain%20Javascript%20-%20Implicit%20Flow)

## What can I use these for
OpenId Connect is a great way to add user authentication to your application
where you are depending on another party to manage the user identities.

In this case mIDentity Box can manage the identity of your users making it
faster to get up and running.

## Single Sign On (SSO)
By implementing OpenId Connect via mIDentity Box you are creating a
session which can be used to single sign on from your custom app
into other apps that your users may have access to via the mIDentity Box portal

## MFA
If MFA is enabled for a user in mIDentity Box then they will be prompted to
enter a token during the authentication. mIDentity Box takes care of all of this
for you, making strong authentication much easier to implement in your app.

## Requirements
In order to run any of the examples you will need to create an OpenId Connect
app in mIDentity Box Admin portal. You can [read more about how to do that after login to mIDentity One.

If you don't have a mIDentity Box account [you can sign up here](https://midentitybox.com/selfenrollment).
