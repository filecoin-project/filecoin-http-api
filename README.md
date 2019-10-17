# filecoin-http-api (WIP)
OpenAPI specification for the Filecoin HTTP REST API. 

The HTML version of the documentation can be [viewed here](https://filecoin-project.github.io/filecoin-http-api/).

This is the specification for the HTTP REST API (to be) implemented by Filecoin nodes. Some details of its design and rationale can be found in this [Design Document](https://docs.google.com/document/d/1ANnTHOU-8612ayvvS7Ru4B1L4voojLE0R0TQ8zF1x5s/edit#heading=h.8v8p3fl8e3gj). 

## Setup 
To facilitate development and review we're using [speccy](https://github.com/wework/speccy) as a linter and [redoc](https://github.com/Redocly/redoc) to generate HTML documentation. You can install them using NPM or Yarn.

```sh
$ npm install
# or
$ yarn install
```

## Usage
To view the specification in HTML form you can invoke redoc via:
```sh
$ npm run serve
```
And view the resulting documentation at http://localhost:5000.

## License
Dual MIT and Apache 2
