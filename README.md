# Create New ReactNative Project

## react-native cli

Gebruik react-native cli om een nieuw project te initialiseren. Geef een stable version mee, in dit geval: 0.57.0

```
react-native init <ProjectName> --version react-native@0.57.0

cd ProjectName

npm add --save-dev @babel/runtime
npm install
```

## ESLint config
```
npm install --save-dev eslint-config-rallycoding
```

Add file `.eslintrc`
```json
.eslintrc
{
	"extends": "rallycoding"
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
