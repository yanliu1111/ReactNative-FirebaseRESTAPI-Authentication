# React Native Expo – Authentication using Firebase Auth REST API

## Main Tech:

- React Native w Expo
- Firebase Authentication, Realtime database
- Components, AuthContext, Utility
- yarn

## Main Dependencies:

- @react-native-async-storage/async-storage
- @react-navigation/native"
- axios

🎃 I built a basic authentication flow with user signup and login, then login a user can fetch data from Realtime database from firebase under setting protected resources.
⚽ Setting the auth token for user authentication on the device and getting access to protected resources thereafter.
Using AuthContext stored the token on the device, so that it is available the next time the app restarts.
🍎 Using the token to attach outgoing HTTP requests to protected resources to fetch data from such resources with help of that token.
👀 I also has the other Authentication practice React Native Expo using firebase SDK, which can make token expire and refresh simpler.

**Check the Demo:**
![Screenshot](Demo.png)
