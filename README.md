# Docker Secrets
This NPM module loads Docker secrets from the `/run/secrets` directory created by Docker Swarm into a JS object for use within Node.js applications.


```javascript
const secrets = require('docker-secrets');
cosnole.log(secrets);
```
