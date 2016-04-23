# heroku-buildpack-multi

Use multiple buildpacks on your app

This was forked after the original author deprecated his release, and we wished
to keep using it.

## Usage

    $ heroku buildpacks:set https://github.com/samstickland/heroku-buildpack-multi.git

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-nodejs.git#0198c71daa8
    https://github.com/heroku/heroku-buildpack-ruby.git#v86

## License

MIT
