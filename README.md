
# Purescript on Nitrous.IO Quickstart

## First, click the hack button

Fire up a new box, defaults are fine.

[![Hack cschneid/purescript-quickstart on Nitrous](https://d3o0mnbgv6k92a.cloudfront.net/assets/hack-l-v1-4b6757c3247e3c50314390ece34cdb11.png)](https://www.nitrous.io/hack_button?source=embed&runtime=nodejs&repo=cschneid%2Fpurescript-quickstart&file_to_open=README.md)

## Finish Setting up Purescript

Purescript needs its prelude in a certain spot to run correctly so copy it from this repo:

`mkdir -p $HOME/.purescript/prelude`

`cp $HOME/workspace/purescript-quickstart/prelude.purs $HOME/.purescript/prelude/prelude.purs`

Put purescript binaries on the path. Do this for every new shell you open.

`export PATH="$PATH:$HOME/workspace/purescript-quickstart/bin"`

## Install a few more things:

I included pre-built binaries for the purescript compiler, but you still need a few things:

**pulp** - build tool for purescript

`npm install -g pulp`

**http-server**

`npm install -g http-server`

## cd into the project directory

`cd $HOME/workspace/purescript-quickstart`

## Build a js file for the browser

`pulp browserify > main.js`

## Fire up the server and view in browser

`http-server`

Now go to the Preview menu, and select port 8080.  Then open the javascript console (Developer Tools) and see the message printed.



