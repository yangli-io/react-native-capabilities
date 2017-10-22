# React Native Capabilities

It's important to understand that with React Native, anything native can be bridged with Javascript APIs. Hence, react native can do basically anything that is native, however, if it is not a common usage it might require manual work.

Below is a table of native functionalities that can be done with React Native

| Native functionality | Android | iOS | Comments |
| -------------------- | ------- | ----- | ---- |
| Push Notifications | [Yes](https://medium.com/differential/react-native-push-notifications-with-onesignal-9db6a7d75e1e) | [Yes](https://facebook.github.io/react-native/docs/pushnotificationios.html) | For android, this will require some third party integration with one signal |
| Vibration | [Yes](https://facebook.github.io/react-native/docs/vibration.html) | [Yes](https://facebook.github.io/react-native/docs/vibration.html) |
| [Deep Linking](https://en.wikipedia.org/wiki/Mobile_deep_linking) | [Yes](https://facebook.github.io/react-native/docs/linking.html) | [Yes](https://facebook.github.io/react-native/docs/linking.html) |
| Device Storage | [Yes](https://facebook.github.io/react-native/docs/asyncstorage.html) | [Yes](https://facebook.github.io/react-native/docs/asyncstorage.html) |
| Geolocation | [Yes](https://facebook.github.io/react-native/docs/geolocation.html) | [Yes](https://facebook.github.io/react-native/docs/geolocation.html) |
| Clipboard | [Yes](https://facebook.github.io/react-native/docs/clipboard.html) | [Yes](https://facebook.github.io/react-native/docs/clipboard.html) |
| Camera Roll | [Yes](https://facebook.github.io/react-native/docs/cameraroll.html) | [Yes](https://facebook.github.io/react-native/docs/cameraroll.html) |
| [NFC](https://en.wikipedia.org/wiki/Near-field_communication) | [Yes](https://github.com/Novadart/react-native-nfc) | [Yes](https://github.com/Novadart/react-native-nfc) | Not very strong support, but the support is there |
| Google Analytics | [Yes](https://github.com/idehub/react-native-google-analytics-bridge) | [Yes](https://github.com/idehub/react-native-google-analytics-bridge) |
| Touch ID | [Yes](https://github.com/naoufal/react-native-touch-id) | [Yes](https://github.com/naoufal/react-native-touch-id) 
| Camera | [Yes](https://github.com/lwansbrough/react-native-camera) | [Yes](https://github.com/lwansbrough/react-native-camera) |
| Barcode Scanner | [Yes](https://github.com/lwansbrough/react-native-camera) | [Yes](https://github.com/lwansbrough/react-native-camera) |
| Webviews | [Yes](https://facebook.github.io/react-native/docs/webview.html) | [Yes](https://facebook.github.io/react-native/docs/webview.html) |
| Background Geolocation | [Yes](https://github.com/transistorsoft/react-native-background-geolocation) | [Yes](https://github.com/transistorsoft/react-native-background-geolocation) | Android module requires purchasing licence |
| Map | [Yes](https://github.com/airbnb/react-native-maps) | [Yes](https://github.com/airbnb/react-native-maps) | Maintained and used by Airbnb, hence extremely good support |

Below is a table of functionalities unique to React Native
| Functionality | Description |
| ------------- | ----------- |
| [Expo](https://expo.io/) | Fast development environment with hot reloading, easy deployment to multiple devices. |
| [Chrometools](https://facebook.github.io/react-native/docs/debugging.html) | Connection to chrometools to use the connect to your favour tools on Google Chrome |
| [SVG](https://github.com/react-native-community/react-native-svg) | Easily use svg |
| [Autoupdater](https://github.com/redbooth/react-native-auto-updater) | Update your app without uploading a new version on the app store (This may have some limitations for certain apps due to app store policies) |
| [React Web](https://github.com/necolas/react-native-web) | To share some react native view components code with the web |



