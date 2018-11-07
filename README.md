# Create New ReactNative Project

## react-native cli

Gebruik react-native cli om een nieuw project te initialiseren. Geef een stable version mee, in dit geval: 0.57.0

```
react-native init <projectname> --version react-native@0.57.0

cd <projectname>

npm add --save-dev @babel/runtime
npm install
```

## ESLint config
```
npm install --save-dev eslint-config-rallycoding
```

Bestand `.eslintrc` toevoegen in de root van je net gecreërde ReactNative applicatie
```json
{
  "extends": "rallycoding",
  "rules": {
    "import/no-extraneous-dependencies": 0
  }
}
```
## Run Project

Voor iOS
```
react-native run-ios
```

Voor Android
```
react-native run-android
```
