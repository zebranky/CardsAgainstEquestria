# Cards Against Equestria
=====================

// TODO

## Overview

## Adding new sets
<https://gist.github.com/Rylius/8056313>

## Credits

## Running your own instance

### Requirements
- node.js
- Grunt (sudo npm install -g grunt-cli)
- PostgreSQL (or MySQL if you're willing to risk unknown weirdness)

### Installation
- make a DB
- set up the DB
  - use res/database/cae.sql for PostgreSQL, or hack up something to use orm's sync function
  - I should add a cae_mysql.sql thing
- rename the config file to config.json and edit it in the obvious places
- run grunt to compile static assets
- `node app.js` to run the server
- use supervisor or something to run the app more automagically
