heroku-buildpack-imagemagick
=================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for vendoring the ImageMagick binaries into your project.

This one actually works :)

### Changing version
Go to https://www.imagemagick.org/download/releases and find a version you want (*.tar.gz). Edit the `bin/compile` file and change out the version number. Clear cache, as shown below, and redeploy your app to Heroku.
