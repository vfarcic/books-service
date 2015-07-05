Development
===========

Install dependencies
--------------------

With [Node.js](http://nodejs.org) and npm installed, run:

```bash
npm run deps
```

Run tests
=========

```sh
sudo npm install -g json-server
json-server test/server/db.json --routes test/server/routes.json
gulp watch
```