# node-red-contrib-advanced-logger

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A Node-RED Logging module.

[`Advanced Logger`](https://www.npmjs.com/package/node-red-contrib-advanced-logger) provides logging controls for Node-Red logging. 
It was originlly forked from [`Advance Logger`](https://www.npmjs.com/package/node-red-contrib-advance-logger)

## Installation

Install `node-red-contrib-advanced-logger` using [npm](https://www.npmjs.com/)

```bash
npm install --save node-red-contrib-advanced-logger
```

## Features

* Log to File, Console and Node-Red Debug window
* Log archiving.
* Log rotating.
* Logging levels.

## Usage

To use the node, launch Node-RED (see [running Node-RED](http://nodered.org/docs/getting-started/running.html) for help getting started).

The input payload should be JSON. 

Any attribute in the payload JSON can be use as the info type logging.

The input payload JSON should have following properties for warning and error logging.

* `warn` – warning logging
* `error` – error logging

## License

MIT © `Marc Neubauer`

[npm-url]: https://www.npmjs.com/package/node-red-contrib-advanced-logger
