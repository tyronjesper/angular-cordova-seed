angular-cordova-seed
====================

Naked Cordova application backed with AngularJS. Includes just core things.

To run application with node.js do the followings:

1. If you do not have cordova install it first with node.js.
   ```
   npm install -g cordova
   ```

2. In order to build application you need to specify a set of target platforms. To achieve this o to angular-cordova-seed folder and run any of these:

   ```
   cordova platform add ios
   cordova platform add android
   cordova platform add blackberry
   
   //if you are on windows
   cordova platform add wp7
   cordova platform add wp8
   ```

3. To build application for all platforms run:
   ```
   cordova build
   ```
   For specific platform:
   ```
   cordova build android
   cordova build ios
   cordova build blackberry
   ```

4. Finally run the app on emulator
   ```
   cordova emulate android
   ```
