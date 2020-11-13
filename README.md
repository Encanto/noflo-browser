# noflo-browser

## Fork notes
This is a fork of the noflo-browser project.  It serves noflo-browser components.  The purpose of the fork is to include our own custom components.  Components are added / removed by modifying the dependencies from package.json.

## Original Readme

A build of [NoFlo](https://noflojs.org) for browser, used as default runtime in [Flowhub](http://app.flowhub.io).
Deployed to `https://noflojs.org/noflo-browser/everything.html`

Based on [noflo-browser-app](https://github.com/noflo/noflo-browser-app),
which should be used as a template if you want to make a custom build for your project.

## Running locally

* Clone this repository
* Install dependencies with `npm install`
* Build the project with `npm run build`
* Start a server with `npm start`

Then go to [Flowhub](http://app.flowhub.io), open any NoFlo browser project, and switch to your local runtime address (by default <http://localhost:3000/browser/everything.html>)
