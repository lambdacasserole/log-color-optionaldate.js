# Log.js (with color and optional timestamps)

This package is a fork of [log-color.js](https://github.com/futoase/log-color.js) which it itself a fork of [Log.js](https://github.com/tj/log.js).

## Installation

Install using [npm](https://www.npmjs.com/):

```
$ npm install log-color-optionaldate
```

## Example

Can be used in a similar fashion to [Log.js](https://github.com/tj/log.js).

Code snippet:

```
var Log = require('log-color-optionaldate');
var log = new Log('info');
log.info('Sent a message to the user@example.com');
```

### Enabling Color

Enable color like this:

```
var Log = require('log-color-optionaldate');
var log = new Log({ level: 'debug', color: true, date: false });
log.warning('Failed to send a message to the user@example.com');
```

## Log Levels

The same log levels are available as in [Log.js](https://github.com/tj/log.js):

```
log.alert('alert');
log.critical('critical');
log.error('error');
log.warning('warning');
log.notice('notice');
log.info('info');
log.debug('debug'); 
```
