<img alt="React Native Login Screen" src="assets/logo.png" width="1050"/>

[![Battle Tested ✅](https://img.shields.io/badge/-Battle--Tested%20%E2%9C%85-03666e?style=for-the-badge)](https://github.com/WrathChaos/react-native-login-screen)

[![Fully Customizable & React Native Login Screen](https://img.shields.io/badge/-Fully%20Customizable%20%26%20Ready%20to%20Use%20Login%20Screen-lightgrey?style=for-the-badge)](https://github.com/WrathChaos/react-native-login-screen)

[![npm version](https://img.shields.io/npm/v/react-native-login-screen.svg?style=for-the-badge)](https://www.npmjs.com/package/react-native-login-screen)
[![npm](https://img.shields.io/npm/dt/react-native-login-screen.svg?style=for-the-badge)](https://www.npmjs.com/package/react-native-login-screen)
![Platform - Android and iOS](https://img.shields.io/badge/platform-Android%20%7C%20iOS-blue.svg?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<p align="center">
  <img alt="React Native Login Screen" src="assets/Screenshots/example.png" width="49%" />
  <img alt="React Native Login Screen" src="assets/Screenshots/example.gif" width="49%" height="735" />
</p>

## Installation

Add the dependency:

### React Native:

```ruby
npm i react-native-login-screen
```

## Peer Dependencies

###### IMPORTANT! You need install them.

```
"react": ">= 16.x.x",
"react-native": ">= 0.55.x",
"react-native-vector-icons": ">= 6.6.0",
"@freakycoder/react-native-helpers": "0.1.0",
"react-native-improved-text-input": ">= 0.0.1",
"react-native-dynamic-vector-icons": ">= 0.2.1"
```

## Import

```js
import LoginScreen from "react-native-login-screen";
```

# Usage

#### 😍 One Line Code to Get The Whole Login Screen ! 🎉

```js
<LoginScreen />
```

# Customizable Advanced Usage

Fully Customizable & Ready to Use Login Screen. You can customize anything on the login screen. Check the example :)

<p align="center">
  <img alt="React Native Login Screen" src="assets/Screenshots/custom-example.png" />
</p>

```js
<LoginScreen
  source={{
    uri: bgImage
  }}
  onPress={loginPressed}
  loginButtonBackgroundColor="#a2a5a9"
  logoComponent={your-logo-component}
  passwordIconComponent={your-icon-component-for-password}
  usernameIconComponent={your-icon-component-for-username}
  onSwitchValueChange={switchValue => {
    setSwitchValue(switchValue);
  }}
  switchValue={switchValue}
  usernameOnChangeText={username => setUsername(username)}
  passwordOnChangeText={password => alert("Password: ", password)}
>
  <View
    style={{
      position: "relative",
      alignSelf: "center",
      marginTop: 64
    }}
  >
    <Text style={{ color: "white", fontSize: 30 }}>{switchValue}</Text>
  </View>
</LoginScreen>
```

### Configuration - Props

#### Coming Soon !

# Change Log

## [0.2.0](https://github.com/WrathChaos/react-native-login-screen/tree/0.2.0) (2019-12-09)

[Full Changelog](https://github.com/WrathChaos/react-native-login-screen/compare/0.1.12...0.2.0)

## [0.1.12](https://github.com/WrathChaos/react-native-login-screen/tree/0.1.12) (2019-12-05)

[Full Changelog](https://github.com/WrathChaos/react-native-login-screen/compare/0.1.11...0.1.12)

## [0.1.11](https://github.com/WrathChaos/react-native-login-screen/tree/0.1.11) (2019-09-29)

\* _This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)_

### Roadmap

- [ ] Configuration - Props COMING SOON
- [x] ~~LICENSE~~
- [x] ~~Android Design Bug Fixes~~
- [ ] Write an article about the lib on Medium

## Author

FreakyCoder, kurayogun@gmail.com

## License

React Native Login Screen is available under the MIT license. See the LICENSE file for more info.
