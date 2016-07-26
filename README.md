# React Native

## Installation

Install cli tools first
```
brew install node
brew install watchman
npm i -g react-native-cli
```

create a new react native project
```
react-native init ReactNativeProject
cd ReactNativeProject
react-native run-ios
```

[ref = https://facebook.github.io/react-native/docs/getting-started.html]

## Project folder structure

```
+ android/
+ ios/
- .buckconfig
- .flowconfig
- .gitignore
- .watchmanconfig
- index.android.js
- index.ios.js
- package.json
```

`android/` and `ios/` are compiled sources
our sources is the `index.*.js`
note that it's no difference in code between `index.android.js`
and `index.ios.js`, they just has a difference detail message
