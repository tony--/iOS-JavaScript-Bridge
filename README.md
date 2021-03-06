# iOS JavaScript to Objective-C Bridge.

## What Does It Do?

Enables method calls and communication between JavaScript & Objective-C. Allows you to write application logic in JavaScript and control native device features via JS to Obj-C calls.

## How Does It Work?

Your JS is contained and executed inside a custom build of JavaScriptCore so that no private API calls are made (and therefore your project can be deployed to the Apple App Store). No webview is presented to the user by default so your app does not "run" inside a web browser.

Instead you can create your application logic and call native methods entirely in JavaScript. This opens up a number of possibilities such as allowing JavaScript to control OpenGL output making game engines that are coded in JavaScript capable of using native-speed graphics output instead of using Safari and the HTML canvas tag.

## Future Plans?

Right now, any methods that you expose to JavaScript must be written by yourself so an understanding of Objective-C is required. Future versions of this project will expose a rich API to your JavaScript code to allow control of the most useful native capabilities of the device.

As the project progresses many more features will be added to the list. The main priorities of this project are to make these features available to JavaScript as an API:

* Mimic canvas-tag methods to output graphics via OpenGL.
* Mimic audio-tag methods to output sound via OpenAL.
* Provide a clean and easy networking API to JavaScript to utilise native sockets capability.

## License

Open-source version licensed for non-commercial use only. If you would like to use this project in a commercial application please purchase a commercial license from http://www.isogenicengine.com/store/ios-javascript-wrapper-bridge/. Commercial licenses are VERY cheap! Have a look!