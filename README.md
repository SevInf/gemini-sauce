# gemini-sauce
Plugin for starting up Sauce Connect when running tests with Gemini

[![Build Status](https://travis-ci.org/Saulis/gemini-sauce.svg?branch=master)](https://travis-ci.org/Saulis/gemini-sauce)

## Notes
Requires a version of gemini that supports plugin loading. See https://github.com/bem/gemini/pull/127

## Installation
`npm install gemini-sauce`

## Configuration
- __username__ (optional) sets the username for Sauce Connect. Defaults to environmental variable SAUCE_USERNAME
- __accessKey__ (optional) sets the accesskey for Sauce COnnect. Defaults to environmental variable SAUCE_ACCESS_KEY

Set the configuration to your `.gemini.yml`

```
plugins:
  sauce:
    username: foo
    accessKey: bar
```
