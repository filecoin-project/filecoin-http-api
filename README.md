# node-http-api (WIP)
OpenAPI specification for the Filecoin HTTP REST API. 

This is the specification for the HTTP REST API (to be) implemented by Filecoin nodes. Some details of its design and rationale can be found in this [Design Document](https://docs.google.com/document/d/1ANnTHOU-8612ayvvS7Ru4B1L4voojLE0R0TQ8zF1x5s/edit#heading=h.8v8p3fl8e3gj). 

## Setup 
To facilitate development and review of this specification we're using [speccy](https://github.com/wework/speccy). You can install speccy using NPM or Yarn.

```sh
$ npm install
# or
$ yarn install
```

## Usage
To view the specification in HTML documentation form ([ReDoc](https://github.com/Redocly/redoc)) you can invoke speccy via:
```sh
$ npm run serve
```
And view the resulting documentation at http://localhost:5000.
