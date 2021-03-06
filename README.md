# Tabio

### Effortless tab management for Chrome

Tabio is a Chrome extension designed to make managing lots of browser tabs significantly easier. The extension generates a searchable, scrollable and fully keyboard-accessible list of all open browser tabs.

Available on the [Google Chrome Webstore](https://chrome.google.com/webstore/detail/tabio/bgbhfmeabcmpjblimfddkeikogidjhao).

## Contributing

Contributions of any kind are always welcome. Help make Tabio better by submitting a bug report, feature request or pull request. Please refer to the [contribution guidelines](CONTRIBUTING.md) for more infomation.

### Development Dependencies

| Name    | Installation                                                                       |
|---------|------------------------------------------------------------------------------------|
| Node.js | [Instructions](http://nodejs.org/download/)                                        |
| Bower   | [Instructions](http://bower.io/#install-bower)                                     |
| Gulp    | [Instructions](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md) |

### Setup

* Clone the repository

```
$ git clone https://github.com/colebemis/tabio.git
$ cd tabio
```

* Install npm dependencies

```
$ npm install
```

* Install bower dependencies

```
$ bower install
```

* Create the initial build

```
$ gulp build
```

* Load the extension

  - Open Google Chrome and type `chrome://extensions` inside the address bar
  - Enable `Developer mode`
  - Click on `Load unpacked extension`
  - Select the `/dist` folder

### Gulp Tasks

| Task    | Description                                   |
|---------|-----------------------------------------------|
| `build` | Compile, minify and copy the extension files  |
| `zip`   | Create a zip archive for publishing           |

## License

Tabio is licensed under the [MIT License](LICENSE.md).
