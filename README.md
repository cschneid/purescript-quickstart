
# Purescript on Nitrous.IO Quickstart

## Install a few more things:

I included pre-built binaries for the purescript compiler, but you still need a few things:

**Pulp** - build tool for purescript

`npm install -g pulp`

**http-server**

`npm install -g http-server`

## Put purescript binaries on the path

`export PATH="$PATH:$HOME/workspace/purescript/bin"`


## Build a js file for the browser

`pulp browserify > main.js`

## Fire up the server and view in browser

`http-server`

Now go to the Preview menu, and select port 8080.  Then open the javascript console (Developer Tools) and see the message printed.



