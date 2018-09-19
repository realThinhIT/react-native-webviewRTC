
# react-native-webview

## Getting started

`$ npm install react-native-webviewRTC --save`

### Mostly automatic installation

`$ react-native link react-native-webviewRTC`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNWebviewPackage;` to the imports at the top of the file
  - Add `new RNWebviewPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-webviewRTC'
  	project(':react-native-webviewRTC').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-webview/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-webviewRTC')
  	```


## Usage
```javascript
import WebViewAndroid from 'react-native-webviewRTC';

// TODO: What to do with the module?
WebViewAndroid;
```
  