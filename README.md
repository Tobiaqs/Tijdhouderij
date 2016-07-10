# Tijdhouderij
VIC-Sterksel: app for keeping time without user interaction, using proximity beacons.

## Prepare environment
`npm install -g cordova ionic bower gulp-cli`

Installs Cordova, Ionic, Bower and Gulp globally.

- Cordova: Platform on which Ionic was built
- Ionic: Tool that allows you to build and deploy easily
- Bower: Package manager for frontend libraries
- Gulp: build system

`npm install`

Installs Node.JS libraries, and frontend libraries using Bower.

### Android
- `ionic platform add android`
- `ionic resources`
- `ionic state restore`

`ionic run android`

### iOS
- `ionic platform add ios`
- `ionic resources`
- `ionic state restore`

Now you can open platforms/ios/VAA Maps/VAA Maps.xcodeproj in XCode.

## Notes
- Do not commit platform.json with a "cordovaPlatforms" value other than [].