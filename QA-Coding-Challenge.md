# Coding Challenge
This page consists coding challenge for QA and QA Lead roles at Isentia.

# Challenge - 

Write tests to load the Isentia (http://www.isentia.com/) website , navigate to product&services -> isentia.mediaportal page and verify the three modules of media portal displayed.
Tests must include verifying the no.of modules displayed and the names.

## Functional requirements

* Tests are run on the command line using `npm test`
* Tests are run against a configurable host, with `http://www.isentia.com/` as the default
* Tests can be configured to run various browser and OS combinations against a testing service (SauceLabs or BrowserStack), at a minimum the following should be included
  * IE10, Windows 8
  * Chrome latest, Windows 8
  * Safari latest, Mac OS latest
* Testing service credentials are passed as environment variables

## Non-functional requirements

* Tests are written in javascript, using NodeJS
* Tests are written against using protractor
* Tests cases describe expected behavior
* Need to follow Page object model
* Style guide: https://github.com/busbud/js-style-guide

### Bonus

* Tests run against mobile browsers
* Tests capture screenshots of failures

## What we're looking for

1. POM approach to project structure and use of generic xpaths/css paths
2. Using high-quality existing libraries or small amounts of custom code
3. Showing your work through your commit history
3. Polish
4. Pride in craftsmanship

## References

* https://docs.saucelabs.com/tutorials/node-js/
* http://www.browserstack.com/automate/node
