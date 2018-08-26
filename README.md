<p align="center">
  <h1 align="center">
    size-plugin
    <a href="https://www.npmjs.org/package/size-plugin"><img src="https://img.shields.io/npm/v/size-plugin.svg?style=flat" alt="npm"></a>
  </h1>
</p>
在 打包过程中显现具体打包后的文件大小
<p align="center">
  Prints the gzipped sizes of your webpack assets and the changes since the last build.
</p>

<p align="center">
  <img src="https://i.imgur.com/3bWBrJm.png" width="602" alt="size-plugin">
</p>


## Installation

Install `size-plugin` as a development dependency using npm:

```sh
npm i -D size-plugin
```

---

## Usage

Add an instance of the plugin to your webpack configuration:

```diff
// webpack.config.js
+ const SizePlugin = require('size-plugin');

module.exports = {
  plugins: [
+    new SizePlugin()
  ]
}
```

---

## License

[Apache 2.0](LICENSE)

This is not an official Google product.
