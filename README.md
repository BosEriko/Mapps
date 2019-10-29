# Mapps

## Status: Development

A generic Maps App.

- Planned Technology Stack
  - React Native
  - Redux
  - Ruby on Rails
  - GraphQL
  - Trailblazer
  - Maps API
  - Google Translate API
- Most Viable Product Features
  - [ ] Simple Authentication
  - [ ] Basic Profile
  - [ ] Current Location (Maps)
  - [ ] ...

## Expo Setup

Before we get started be sure to install all the dependencies for this project. Inside the directory run:

```
yarn install
```
_Note: Please always use Yarn so that you don't generate package-lock.json by mistake_

Then install Expo globally to use its CLI:

```
npm install -g expo-cli
```

Before running your app on iOS, make sure you have CocoaPods installed and initialize the project:

```
cd MappsExpo/ios
pod install
```

Then you can run the project:

```
cd MappsExpo
yarn android
yarn ios
```

## Run the project

On the web:

```
npm run web
```

On your Android device:

```
npm run expo
```

As React Native only:

```
npm start
```

## Run Tests

Tests use Jest and you can run it with this command:

```
npm run test
```
