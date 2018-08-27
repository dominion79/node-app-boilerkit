# GOVUK startkit

A simple starter kit to start writing node app with the gov uk front end toolkit.


## Getting started
Install dependencies using `yarn install` ensure you are using >= `Node v8.4.0`

Ensure you have a `.env` file containing all default env variables

`cp .env-template .env`

**Starting the app**

### Build assets
`yarn build`

### Start the app.

Ensure you build assets first

`yarn start`

### Runing the app in dev mode**

`yarn start:dev`

### Run linter

`yarn lint`

### Run tests

`yarn test`


## Gotchas
If you get this error when starting the app:
`Cannot find module './build/Release/DTraceProviderBindings'`

See for more details:

https://stackoverflow.com/questions/37550100/cannot-find-module-dtrace-provider

Run

`npm rebuild dtrace-provider`

## Dependency information 

| Package | Version | Summary | 
|---------|---------|---------|
| body-parser | ^1.18.2 | To handle HTTP POST request in Express.js version 4 and above |
| bunyan" | ^1.8.12 | JSON logging |
| bunyan-format | 0.2.1 |
| bunyan-request-logger | ^1.1.0 |
| compression | ^1.7.2 | Compression middleware | 
| cookie-parser | ~1.4.3 | 
| cookie-session | ^2.0.0-beta.3 | 
| csurf | ^1.9.0 | CSRF token middleware |
| debug | ~3.1.0 | 
| dotenv | ^5.0.1 | loads environment variables from a .env | 
| ejs | ~2.5.8 | Template framework |
| express | ~4.16.3 | 
| express-request-id | ^1.4.0 | 
| helmet | ^3.12.0 | Helmet helps you secure your Express apps by setting various HTTP headers. It’not a silver bullet, but it can help | 
| http-errors | ~1.6.3 | Create HTTP errors for Express |
| moment | 2.22.1 | Date library for parsing, validating, manipulating, and formatting dates. |
| morgan | ~1.9.0 | Morgan is used for logging request details | 
| node-sass-middleware | 0.11.0 | 
| passport | ^0.4.0 | Authentication middleware | 
| sass-middleware | ^0.0.3 | 