> __DISCLAIMER:__ This app is for experimental use __ONLY__. Do __NOT__ use with your credentials – data transfer is not encrypted. App is __NOT__ designed for any malicious purposes.

# Simple Keyboard Keylogger

This Android keyboard is a Proof of Concept of keylogger hidden in popular thirty-party keyboard app. It is used for testing purposes in experimental part of my Bachelor thesis. App is based on open-source [Simple Keyboard](https://github.com/rkkr/simple-keyboard) app.

## About
Keyboard sends every alphanumeric keystroke with ID of device as a POST request to a REST server ([simple-rest](https://github.com/kovarikl/simple-rest) used). If Internet connection is not available, nothing happens.

App is designed only for proving of concept, thus, data transfer is not encrypted and send as a plaintext HTTP requests.

Address of REST server and ID of device are set in utility class `inputmethod.latin.utils.KeyloggerUtils`.

## Build and run
Keyboard is not available on any official platform. You can side-load it via Android Studio.

## License & Credits

Licensed under Apache License 2.0

This keyboard is based on open-source app [Simple Keyboard](https://github.com/rkkr/simple-keyboard), which is based on AOSP LatineIME keyboard. You can get the original source code in https://android.googlesource.com/platform/packages/inputmethods/LatinIME/.
