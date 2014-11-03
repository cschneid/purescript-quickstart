
# Purescript on Nitrous.IO Quickstart

## First, click the hack button

Fire up a new box.

[![Hack cschneid/purescript-quickstart on Nitrous](https://d3o0mnbgv6k92a.cloudfront.net/assets/hack-l-v1-4b6757c3247e3c50314390ece34cdb11.png)](https://www.nitrous.io/hack_button?source=embed&runtime=nodejs&repo=cschneid%2Fpurescript-quickstart&file_to_open=README.md)

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



