# buildpack-webhook-honeybadger
Beginnings of a Honeybadger deploy buildpack for Gigalixir

## ENV VAR SETUP

In order to get the most from this buildpack, ensure the following ENV vars are set:
  * `HONEYBADGER_API_KEY`
  * `HONEYBADGER_APP_NAME`
  * `HONEYBADGER_APP_ENV`
  * `HONEYBADGER_GIT_REPO`
  
Refer to the code in `bin/compile` for specific uses.
