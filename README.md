# DEPRECATED REPOSITORY

As of Node-RED 3.0, this theme is maintained in the [Node-RED Contrib Theme Collection](https://github.com/node-red-contrib-themes/theme-collection) repository.

DEVELOPERS: If your project uses this theme as a dependency, please update your project as this repository will no longer be maintained.

# Node-RED Contrib Theme: OLED

A [Node-RED][node-red] dark theme for OLED displays.

![screenshot](https://raw.githubusercontent.com/node-red-contrib-themes/oled/master/images/screenshot.png)

This theme is part of the [Node-RED Contrib Theme Collection][theme-collection].

## Install

### Install with npm

Run the following command from within the Node-RED user data directory (by default, `$HOME/.node-red`).

```shell
npm install @node-red-contrib-themes/oled
```

## Usage

Add `theme: "oled"` to the `editorTheme` object in your `settings.js` and then restart Node-RED.

```js
editorTheme: {
    theme: "oled",
},
```

For details on the Node-RED's configuration file and its structure, please refer to the [Node-RED official documentation][node-red-doc].

### Themed Scrollbars (*EXPERIMENTAL*)

Includes the theme and changes the scrollbars to make them better fit the theme.

**NOTE**: This is ***EXPERIMENTAL*** and may not work on all browsers.

Add `theme: "oled-scroll"` to the `editorTheme` object in your `settings.js` and then restart Node-RED.

```js
editorTheme: {
    theme: "oled-scroll",
},
```

### Monaco Editor Theme

This package comes with a pre-configured theme for the Monaco editor.

Just leave `theme` under `codeEditor` commented out in your `settings.js` and then restart Node-RED.

```js
editorTheme: {
    theme: oled,
    codeEditor: {
        lib: "monaco",
        options: {
            // theme: "",
        },
    },
},
```

## License

This project is licensed under the [MIT license][license].

## Like my work?

If you like my work please give it a GitHub ⭐️.

Also, consider supporting me with a coffee ☕.

<a href="https://www.buymeacoffee.com/mbonani" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Buy Me A Coffee" height="60px"></a>

[license]: LICENSE
[node-red-doc]: https://nodered.org/docs/user-guide/runtime/configuration#editor-themes
[node-red]: https://nodered.org/
[theme-collection]: https://www.npmjs.com/package/@node-red-contrib-themes/theme-collection
