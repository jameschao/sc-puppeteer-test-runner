# Puppeteer SproutCore Test Runner

This is a CLI test runner for [SproutCore](https://github.com/sproutcore/sproutcore) based on [Puppeteer](https://github.com/puppeteer/puppeteer).

This is meant to replace the existing [PhantomJS](https://phantomjs.org/)-based CLI [test runner](https://github.com/sproutcore/sproutcore/tree/master/phantomjs) and has the exact same parameters and output (for now).

## Command Line Options
```
SproutCore Puppeteer Test Runner

  Runs unit tests under Puppeteer. Requires sc-server to be running.
  Options below, command line options override environment variables.

Options:

      --host, env[HOST]                  sc-server host [localhost]
      --port, env[PORT]                  sc-server port [4020]
      --include-targets                  Comma-delimited list of targets to include
      --exclude-targets                  Comma-delimited list of targets to exclude
      --target-kinds                     Comma-delimited list of target kinds to include
      --filter                           Regular expression to use to filter tests
      --[no-]experimetal                 Shortcut to control inclusion of experimental framework tests [true]
      --travis, env[TRAVIS]              Running under Travis CI [false]
  -v, --verbose, env[VERBOSE]            Log test assertion results [false]
  -V, --very-verbose, env[VERY_VERBOSE]  Log test page console messages [false]
  -h, --help                             This help page
  ```
