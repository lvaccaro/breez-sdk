# Breez SDK React Native Example

## Prerequisites
You need to set your Breez API key in the relevant places before running the example.
Either Find and Replace `INSERT_YOUR_BREEZ_API_KEY` with your Breez API key, 
or replace `INSERT_YOUR_BREEZ_API_KEY` in the following files:
* `android/app/gradle.properties`
* `ios/Secrets.xconfig`

## Build
Since the example app uses the Breez SDK react native plugin as a local file reference, you need to build the node_modules in the sdk-react-native directory:
```
yarn
```
Then build the node modules in the example directory:
```
yarn
```
Then to install the iOS pods:
```
yarn pods
```

## Run
```
Run android or ios:
```
yarn android
```
or 
```
yarn ios
```
