# Creating App Passwords

App passwords are needed to subscribe to calenders in other applications than the Nextcloud web interface (e.g. Thunderbird or an Android device). They are used as a replacement for the regular login username and password as the latter cannot not be used as the login to the cloud is handled via the [single sign-on](../sso/index.md).

To create an app password, follow the following steps:

1. Log into the [cloud](https://cloud.frisp.org/).
2. Click on your profile image on the top right corner.
3. Click on "Settings".
4. Click on "Security" in navigation bar on the left (under "Personal").
5. In the section "Devices & sessions", enter an app name into the corresponding input field (e.g. `Thunderbird`).
6. Click on "Create new app password".
7. If needed, confirm your password (the regular [single sign-on](../sso/index.md)-password).
8. You can now use the displayed username (the app name) and password as the credentials to subscribe e.g. to the calender from another device.

Note that you can not request the app password for an already created app again! If you loose your app password, delete the app (click on the three dots in the corresponding row and click on "Revoke") and create a new one.