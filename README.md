# Cordova App Template: Web URL Wrapper

This template helps you create a Cordova mobile app that loads your website from a specified URL, effectively turning your web app into a native-like mobile application.

## Features

- Loads any web URL inside a Cordova WebView
- Supports Android and iOS
- Simple configuration

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [Cordova CLI](https://cordova.apache.org/)

### Installation

1. **Create a new Cordova project:**
   ```bash
   cordova create myApp com.example.myapp MyApp
   cd myApp
   ```

2. **Add platforms:**
   ```bash
   cordova platform add android
   cordova platform add ios
   ```

3. **Copy template files:**
   Replace the contents of the `www` folder with the files from this template.

4. **Configure your web URL:**
   Edit `www/js/index.js` and set your desired URL:
   ```javascript
   var webUrl = "https://yourwebsite.com";
   ```

5. **Add the InAppBrowser plugin:**
   ```bash
   cordova plugin add cordova-plugin-inappbrowser
   ```

### Running the App

- **Android:**
  ```bash
  cordova run android
  ```
- **iOS:**
  ```bash
  cordova run ios
  ```

## Customization

- Update the app icon and splash screen in the `res` folder.
- Modify `config.xml` for app metadata.

## License

MIT

---

**Note:** Make sure your website supports mobile devices and uses HTTPS for best results.