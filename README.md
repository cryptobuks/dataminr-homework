Twitter Lexicon
=======================
This project was bootstrapped with [the React Redux Starter Kit](https://github.com/davezuko/react-redux-starter-kit).

Requirements
------------

* node `^4.2.0`
* npm `^3.0.0`

Getting Started
---------------

Just clone the repo and install the necessary node modules:

```shell
$ git clone https://github.com/julianvmodesto/tweetstat.git
$ cd tweetstat
$ npm install                   # Install Node modules listed in ./package.json (may take a while the first time)
$ npm start                     # Compile and launch
```
To disable the sidebar redux devtools, use ctrl+h or run `npm run dev:no-debug` instead.

Usage
-----

The npm scripts were provided by the React Redux Starter Kit.

* `npm start` - Spins up Koa server to serve your app at `localhost:3000`. HMR will be enabled in development.
* `npm run dev` - Same as `npm start`, but enables nodemon to automatically restart the server when server-related code is changed.
* `npm run dev:no-debug` - Same as `npm run dev` but disables redux devtools.

API Secrets
-----
NOTE: private Dataminr endpoints and my NYT API key were removed with BFG-repo-cleaner so this will not work out of the box
