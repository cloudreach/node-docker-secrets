# Docker Secrets
This NPM module loads Docker secrets from the `/run/secrets` directory created by Docker Swarm into a JS object for use within Node.js applications.

## Installation
```bash
npm install @cloudreach/docker-secrets
```

## Usage
```javascript
const secrets = require('@cloudreach/docker-secrets');
console.log(secrets);
```
