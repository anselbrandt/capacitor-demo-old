## Created with Capacitor Create App

This app was created using [`@capacitor/create-app`](https://github.com/ionic-team/create-capacitor-app),
and comes with a very minimal shell for building an app.

### Running this example

To run the provided example, you can use `yarn start` command.

```bash
yarn start
```

### iOS

Install cocoapods:

```
sudo gem install cocoapods
```

```
yarn add @capacitor/ios

npx cap add ios

yarn build

npx cap open ios

npx cap run ios
```

If `npx cap run ios` fails:

```
sudo xcode-select -s /Applications/Xcode.app/Contents/Developer
```