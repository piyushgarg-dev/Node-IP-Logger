# IPFY - IP Logger

Ipfy is a simple middleware for node.js that loggs the incomming request and writes to a file ```logs.txt ```
## Install
## ```npm i ipfy```
## Usage
## ```Express.js```

```javascript
const express= require('express');
const log = require('ipfy');

const app = express();

// Log middleware
app.use(log.logger);

app.get('/)...
```
## That's it and you are done
