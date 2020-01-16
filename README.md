# Heroku Buildpack for Ghostscript

Currently installs LibreOffice 6.3.4 on Heroku.

## Install

    $ cd /path/to/your-app
    $ heroku buildpacks:add https://github.com/notarize/heroku-buildpack-libreoffice.git

    # Push changes to deploy
    $ git push

    # This version of ghostscript will end up deployed at /app/vendor/libreoffice/bin/
