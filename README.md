# Demonstration of [paper-input#375](https://github.com/PolymerElements/paper-input/issues/375)

## Local

1. Start an http server serving files in this directory
   (e.g. `python -m SimpleHTTPServer`)
1. Open http://localhost:8000/index.html in Safari (adjust port as necessary)

## Remote

Alternatively, visit http://jab.github.io/paper-input-issue-375/ in Safari

## Reproduction Steps

1. Click the Submit button leaving inputs invalid
1. Observe webshim-polyfilled error bubble don't work as expected
