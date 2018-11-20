# Create New ReactNative Project

## react-native cli

Gebruik react-native cli om een nieuw project te initialiseren. Geef een stable version mee, in dit geval: 0.57.0

```
react-native init <projectname> --version react-native@0.57.0

cd <projectname>

npm add --save-dev @babel/runtime
npm install
```

## Add React Navigation 2.X.X (if needed)

### remove version 3.X.X of React Navigation
Wanneer je een verkeerde versie van React Navigation aan je project zou hebben toegevoegd (bv 3.0.0) kan je deze met onderstaand commando verwijderen. (deze wordt dan ook verwijderd uit de package.json)
```
npm uninstall react-navigation
```

## add version 2.X.X of React navigation
```
npm install --save react-navigation@"<3.0.0"
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
