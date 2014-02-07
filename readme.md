# Diplomat

[issues]: https://github.com/garbados/diplomat/issues
[license]: http://opensource.org/licenses/MIT

A conflict viewer for CouchDB and Cloudant

## Install

Diplomat runs as a couchapp living inside a CouchDB or Cloudant database, so make sure that database is created and running before you start. Then:

    git clone git@github.com:garbados/diplomat.git
    cd diplomat
    npm install && bower install
    grunt deploy --database DATABASE

... and visit <http://localhost:5984/DATABASE/_design/diplomat/_rewrite> to see it.

## Test

Diplomat uses Mocha for tests. To run them, do:

    npm test

Which will run the test suite. To run the tests, and run them again whenever anything changes, do:

    grunt watch-test

Enjoy!

## Contribute

If you want to contribute to Diplomat, yay! Here are a couple ways to help:

* File an [issue][issues], if anything went wrong.
* File an [issue][issues], if you wish Diplomat did more.
* Pick an [issue][issues] to hack on!

I'm happy to help you, if you want to contribute code, or otherwise don't know where to start. If you want to tackle an issue but don't know how, leave a note and we can work it out :)

## License

[MIT][license], yo.
