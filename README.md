#cli-clear
> Cross-platform clear for the CLI with Node.JS

## Getting Started
This plugin requires NodeJS `~0.8.0`

Just a simple script for clearing the console. ASCII tricks don't work in Windows.

```shell
npm install cli-clear -g
```

## Overview

```javascript
var clear = require("cli-clear");

clear();
```

### Arguments
#### callback
Type: `Function`  

Useful when using asynchronous prompts so that your prompts appear *after* the clear.

## Release History
* 0.1.0 initial release

---

[![Analytics](https://ga-beacon.appspot.com/UA-3614308-6/stevenvachon/cli-clear)](https://github.com/igrigorik/ga-beacon "Google Analytics") [![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/stevenvachon/cli-clear/trend.png)](https://bitdeli.com/free)
