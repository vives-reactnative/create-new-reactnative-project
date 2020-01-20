# Create New ReactNative Project

## Expo cli

Gebruik de Expo cli om een nieuw project te initialiseren. 

```
expo init <projectname>
cd <projectname>
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

```
npm start
```

### Expo client app

Installeer de Expo client app op je iOS of Android mobiele toestel en connecteer op hetzelfde wireless netwerk als je computer.

Log in met je Expo account zowel op je laptop als op de Expo client app.

Open je nieuwe React Native applicatie in de Expo client app.

## Add React Navigation 

We werken steeds met React Navigation versie 4.x

### Basis react-navigation libraries (required)
```
expo install react-navigation react-native-gesture-handler react-native-reanimated react-native-screens
```

### StackNavigator (optioneel: indien je project stacknavigatie bevat)
```
expo install react-navigation-stack @react-native-community/masked-view
```

### TabNavigator (optioneel: indien je project tabnavigatie bevat)
```
expo install react-navigation-tabs
```

## Add Axios

```
npm i --save axios
```
