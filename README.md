# PWA Profiles for Mobile
This repository contains configuration profiles intended for installing PWAs of popular websites on iOS and iPadOS.

The `.mobileconfig` files are generated using a [shortcut](https://www.icloud.com/shortcuts/2783f3c18699445c846816ee5a2e12ea). They are unsigned.

## Using the shortcut

1. Add and run the shortcut
2. Provide the following details:
   - Profile name - the name of the `.mobileconfig` profile to be generated
   - Profile Maker/Developer - the name of the profile creator
   - Consent text - text to be displayed prior to installation of the profile
   - Description - a short summary of the purpose of the profile
   - Web Clip Name - the name of the website for the PWA
   - URL - the URL of the website
   - Identifier - a unique identifier for the profile
3. Select an image to serve as the PWA icon
4. Save the profile

## Installing the profile

1. Click on the profile in the Files app
2. Go to the Settings app and click on `Profile Downloaded` to initiate the installation process
3. Select `Install` and enter your password if prompted
4. Select `Next` and then `Install` to complete the installation
5. The PWA will be added as a shortcut to the home screen
