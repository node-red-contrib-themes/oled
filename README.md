# OLED Node-RED theme

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE)
[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]

[![NPM Shield][npm-shield]][npm-package]

## About

A [Node-RED][node-red] dark theme for OLED displays.

![screenshot](https://raw.githubusercontent.com/node-red-contrib-themes/oled/master/images/screenshot.png)

## Install

Change to the Node-RED `userDir` directory, usually `~/.node-red`.

```shell
cd ~/.node-red
```

Install this package.

```shell
npm install @node-red-contrib-themes/oled
```

Add the following to the `editorTheme` section of your `settings.js`.

```js
editorTheme: {
    page: {
        css: "<HOME>/.node-red/node_modules/@node-red-contrib-themes/oled/theme.css"
    }
}
```

Replace `<HOME>` with the home directory of the user running Node-RED. For
example, `/home/username`.

For more details on the configuration please refer to the
[Node-RED official documentation][node-red-doc].

Restart Node-RED.

Enjoy!

## Update

Change to the Node-RED `userDir` directory, usually `~/.node-red`.

```shell
cd ~/.node-red
```

Update this package.

```shell
npm update @node-red-contrib-themes/oled
```

Reload the Node-RED page on the web browser.

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
