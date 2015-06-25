# SuperAgent [![Build Status](https://travis-ci.org/fiatjaf/superagent-cors.svg?branch=master)](https://travis-ci.org/fiatjaf/superagent-cors)

**THIS FORK** The only thing this fork does is to remove the default `.type('json')` call that invariably sends a `Content-Type` header, no matter which kind of request you are going to do, and then breaks CORS. For more information about the issue, see https://github.com/visionmedia/superagent/issues/501.

## Installation

```
$ npm install fiatjaf/superagent
```

The module is called `superagent`, not `superagent-cors`, so you can use it in your whole project and you don't need to change any line. New superagent versions will be merged here.

![super agent](http://f.cl.ly/items/3d282n3A0h0Z0K2w0q2a/Screenshot.png)

For more information and documentation, please refer to the original superagent docs: http://visionmedia.github.io/superagent/
