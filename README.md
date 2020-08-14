# Mobile Web/Hybrid/native Apps Test Automation Framework

## Libraries, Tools and Programming language used is as follows

`Javascript` `WebdriverIO` `Appium`

## What is Appium?

- Appium is an `open-source` tool for automating `mobile web`, `native` and `hybrid apps` on `iOS`, `Android`, `Windows` and `macOS` platforms.
- It's a `cross-platform` tool. Meanse it allows us to write tests against different platforms using the same API. This allows `code reuse` between platforms.
- The Appium server is written in Node.JS and can be installed from source or directly from NPM.
- There is also an alternative GUI wrapper.
- There are client libraries which support Appium extension to the WebDriver protocol. One such library is `WebdriverIO` library.

## Dependencies

- [Java SE Development Kit 8](https://www.oracle.com/in/java/technologies/javase/javase-jdk8-downloads.html)
- [Node.js](https://nodejs.org/en/)
- [Android Studio](https://developer.android.com/studio/install)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Appium](http://appium.io/)
- [Appium Test APK](https://github.com/appium/appium/tree/master/sample-code/apps)

## Setup

- `npm i @wdio/cli`
- `./node_modules/.bin/wdio config`
  - `WDIO Configuration Helper`
  - ? Where is your automation backend located? `On my local machine`
  - ? Which framework do you want to use? `mocha`
  - ? Do you want to run WebdriverIO commands synchronous or asynchronous? `sync`
  - ? Where are your test specs located? `./test/specs/\*_/_.js`
  - ? Do you want WebdriverIO to autogenerate some test files? `Yes`
  - ? Do you want to use page objects (https://martinfowler.com/bliki/PageObject.html)? `Yes`
  - ? Where are your page objects located? `./test/pageobjects/\*_/_.js`
  - ? Are you using a compiler? `No!`
  - ? Which reporter do you want to use? `allure`
  - ? Do you want to add a service to your test setup? `selenium-standalone`
  - ? What is the base url? `http://localhost`

## Run

![](data/doc-images/appium-wdio-js-test-cases-execution-gif.gif)

![](data/doc-images/appium-wdio-js-test-cases-execution_.gif)

```
"spec" Reporter:
------------------------------------------------------------------
[emulator-5554 Android 10 #0-0] Spec: C:\Users\jagadeesh\Documents\appium-wdio-js\test\specs\cancelDialog[Activity].js
[emulator-5554 Android 10 #0-0] Running: emulator-5554 on Android 10 executing C:\Users\jagadeesh\Documents\appium-wdio-js\ApiDemos-debug.apk
[emulator-5554 Android 10 #0-0] Session ID: b16c5126-ad7a-4690-b64d-2b42f77959be
[emulator-5554 Android 10 #0-0]
[emulator-5554 Android 10 #0-0] Cancel Dialogs
[emulator-5554 Android 10 #0-0]    ✓ Verify that the cancel dialog short message is correct and displays
[emulator-5554 Android 10 #0-0]    ✓ Verify that the cancel dialog long message is correct and displays
[emulator-5554 Android 10 #0-0]    ✓ Verify that the cancel dialog ultra long message is correct
[emulator-5554 Android 10 #0-0]
[emulator-5554 Android 10 #0-0] 3 passing (24.4s)
------------------------------------------------------------------
[emulator-5554 Android 10 #0-1] Spec: C:\Users\jagadeesh\Documents\appium-wdio-js\test\specs\dialog.test.js
[emulator-5554 Android 10 #0-1] Running: emulator-5554 on Android 10 executing C:\Users\jagadeesh\Documents\appium-wdio-js\ApiDemos-debug.apk
[emulator-5554 Android 10 #0-1] Session ID: f771a92f-096a-4049-a52c-1c74d31cd2c8
[emulator-5554 Android 10 #0-1]
[emulator-5554 Android 10 #0-1] Dialog
[emulator-5554 Android 10 #0-1]    ✓ Verify that the text entry dialog username & password fields are editable
[emulator-5554 Android 10 #0-1]    ✓ Verify that the app adjust when orientation is switched
[emulator-5554 Android 10 #0-1]    ✓ Verify isSelected, isEnabled & isDisplayed
[emulator-5554 Android 10 #0-1]    ✓ Verify Timeouts
[emulator-5554 Android 10 #0-1]    ✓ Verify the repeat alarm options has attribute checked set to true when selected
[emulator-5554 Android 10 #0-1]
[emulator-5554 Android 10 #0-1] 5 passing (1m 15.7s)
```

## Reference

[Mobile Automation with Appium in JavaScript](https://testautomationu.applitools.com/appium-javascript-tutorial/)
