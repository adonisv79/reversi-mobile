# About the project

This project serves as a practice project for applying the latest React Native technologies with Expo + Expo Routing

# How it was built
In order for us to recall our learnings, here are some tidbits to help remind us of the steps we have gone through

1. Make sure to install the lates Android Studio and follow the SDK version needed here https://reactnative.dev/docs/environment-setup#target-os-1

2. The environment path should include where the adb.exe exists (platform-tools).

3. create the React app `npx create-expo-app {my-app-name}`

4. Make sure that you have installed 'Expo Go' app on your mobile device

5. Install Expo CLI in your dev machine `npm i expo`

6. Start the dev server by running `npx expo start` ( QR gets generated)

7. In the Expo Go app, scan the QR code

8. Go to 'App.js' tinker with it by changing the contents of <Text> and it will reflect in the mobile app.

9. created the app using the command `npx create-expo-app@latest --example with-router ./` and agree to install it globally

10. text the cli using `npx expo whoami` which will show "not logged in" but its ok as you do not need to be logged in

11. 

12. created our 'app' folder in root and added 2 files 'index.js' and '_layout.js'

13. in '_layout,js':

``` js
import { Stack } from "expo-router";

export default function Layout() {
  return <Stack />;
}
```

4. in 'index.js':

``` js
import { View, Text } from 'react-native';

export default function Home() {
  return <View>
    <Text>Home</Text>
  </View>
}
```

5.  Add some more dependencies
```
npm i expo-font react-native-dotenv
```

# References
* Setup for react native - https://reactnative.dev/docs/environment-setup#target-os-1
* Initial Setup - https://docs.expo.dev/get-started/installation/#requirements
* Create Project and Run on EXPO GO - https://docs.expo.dev/get-started/create-a-project/