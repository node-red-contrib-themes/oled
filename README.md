# Node-RED Contrib Theme: OLED

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE)
[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]

[![NPM Shield][npm-shield]][npm-package]

<a href="https://www.buymeacoffee.com/mbonani" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Buy Me A Coffee" height="60px" width="217px"></a>

A [Node-RED][node-red] dark theme for OLED displays.

![screenshot](https://raw.githubusercontent.com/node-red-contrib-themes/oled/master/images/screenshot.png)

## Install

Install via npm

```shell
npm install @node-red-contrib-themes/oled
```

## Configuration

Add the following to the `editorTheme` section of your `settings.js`, and then restart Node-RED.

```js
editorTheme: {
    theme: "oled"
},
```

### Themed Scrollbars (EXPERIMENTAL)

This includes the theme and changes to the scrollbars to make them better fit the theme.

**NOTE**: This is ***EXPERIMENTAL*** and may not work on all browsers.

If you want to try it, add the following to the `editorTheme` section of your `settings.js`, and then restart Node-RED.

```js
editorTheme: {
    theme: "oled-scroll"
},
```

### Monaco Editor Themes

This package comes with a pre-configured theme for the Monaco editor.

**NOTE**: Node-RED version 2.1 or newer is required.

If you want to use it, leave the `theme` option under `codeEditor` in your `settings.js` file commented out.

```js
codeEditor: {
    lib: "monaco",
    options: {
        // theme: "vs",
    }
}    
```

For more details on the configuration please refer to the
[Node-RED official documentation][node-red-doc].

Enjoy!

## License

[MIT][license]

[commits-shield]: https://img.shields.io/github/commit-activity/y/node-red-contrib-themes/oled.svg
[commits]: https://github.com/node-red-contrib-themes/oled/commits/master
[last-commit-shield]: https://img.shields.io/github/last-commit/node-red-contrib-themes/oled.svg
[license]: https://github.com/node-red-contrib-themes/oled/blob/master/LICENSE
[license-shield]: https://img.shields.io/github/license/node-red-contrib-themes/oled.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2021.svg
[node-red-doc]: https://nodered.org/docs/user-guide/runtime/configuration
[node-red]: https://nodered.org/
[npm-package]: https://nodei.co/npm/@node-red-contrib-themes/oled
[npm-shield]: https://nodei.co/npm/@node-red-contrib-themes/oled.png
