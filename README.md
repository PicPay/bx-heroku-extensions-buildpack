# Heroku buildpack: installation of binanies not present on Heroku.

# Usage

Example usage:

```shell
$ heroku buildpacks:add https://github.com/bxblue/heroku-extensions-buildpack
```

## Env vars

```shell
PATH="/usr/local/bin:/usr/bin:/bin:/app/vendor/firefox"
LD_LIBRARY_PATH="/usr/local/lib:/usr/lib:/lib:/app/vendor/firefox"
```
<!-- ## Credit
I cloned a portion of this code from @bensomers so that I can configure the variables to create a recent buildpack for Heroku. -->
