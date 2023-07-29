# node-ts-boilerplate
A node with TS boilerplate based on https://fireship.io/lessons/typescript-nodejs-setup/

How does it work?
- The TS compilator watches the src folder for changes and recompiles.
- ts-watch watches for recompiles(onSuccess, onFailure) and executes a command("node ./dist/server.js") 
