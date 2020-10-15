# heroku-buildpack-storybook

## Get Started

This buildpack for heroku is meant to be used after `heroku/nodejs`.
It also needs to be serve. For example with [heroku-buildpack-static](https://github.com/heroku/heroku-buildpack-static.git).

The main case is adding those buildpack to heroku dyno settings part :


## Settings

A `storybook:build` script should be present in your package.json and should output the build in a `docs-build/` folder.

package.json
```json
    "storybook:build": "build-storybook -o docs-build -s public"
```

## Disclaimer

Airfair won't be responsible for eventual damage caused by the use of this repository.

## Credit

Special thanks to those repository :
- https://github.com/SalesforceFoundation/heroku-buildpack-storybook
- https://github.com/aperkaz/storybook-on-heroku
