# periodicjs.ext.dbseed

An extension to import json seeds into periodic mongodb

 [API Documentation](https://github.com/typesettin/periodicjs.ext.dbseed/blob/master/doc/api.md)

## Installation

```
$ npm install periodicjs.ext.dbseed
```


## Usage

### import database (upsert/update) with custom file seed from cli

```
$ node index.js --cli --extension dbseed --task import --file /path/to/file.json
```

### seed database with custom file seed from cli

```
$ node index.js --cli --extension dbseed --task seed --file /path/to/file.json
```

### import sample from cli

```
$ node index.js --cli --extension dbseed --task sampledata
```

##Development
*Make sure you have grunt installed*
```
$ npm install -g grunt-cli
```

Then run grunt watch
```
$ grunt watch
```
For generating documentation
```
$ grunt doc
$ jsdoc2md controller/**/*.js index.js install.js uninstall.js > doc/api.md
```
##Notes
* Check out https://github.com/typesettin/periodicjs for the full Periodic Documentation