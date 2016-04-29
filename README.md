# U-Wheel
Uninventing the wheel of log

## Overview
uw-log provides a simple, non conflicting, log for your applications with editable configurations.


## Install
```bash
npm install uw-log --save
```

## Examples
````javascript
var LOG=  require('Log').newInstance('TEST');
LOG.info('LOG INFO', 'This is a log');
````