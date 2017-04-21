# \<dsc-polymer-jwt-decode\>

[![Build Status](https://travis-ci.org/discovery-tecnologia/dsc-polymer-jwt-decode.svg?branch=master)](http://travis-ci.org/#!/discovery-tecnologia/dsc-polymer-jwt-decode)
![Bower version](https://img.shields.io/bower/v/dsc-polymer-jwt-decode.svg)
![](https://img.shields.io/pypi/l/Django.svg)

Decode payload of JWT token

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Demo

```
$ git clone https://github.com/discovery-tecnologia/dsc-polymer-jwt-decode.git
$ cd dsc-polymer-jwt-decode
$ npm install
$ npm install -g polymer-cli
$ polymer serve
```
Open browser: http://localhost:8080/components/dsc-polymer-jwt-decode/demo/

## Usage

Install with:

```
$ bower i dsc-polymer-jwt-decode --save
```

Example usage:

```html
<dsc-polymer-jwt-decode
    id="jwtDecode"
    token="eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJhcGktYXV0aCIsImlhdCI6MTQ5MjU2NzQzMywiZXhwIjoxNDkyNTc0NjYzLCJ1c2VyIjoiNThhYjg4MGIzYmY5MDQ0ODZmYjI4Yzk2IiwicHJpdmlsZWdlcyI6WyJhZG1pbiJdfQ.2XxAiWNdLC-aA9L_L5MmVmUlqmj9_ox0sJU8byhw1F8"
    valid="{{isValid}}"
    decoded-token='{{tokenPayload}}'></dsc-polymer-jwt-decode>
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
