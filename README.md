# homebrew-datasette

To install [Datasette](https://github.com/simonw/datasette) using Homebrew:

    brew tap simonw/datasette
    brew install simonw/datasette/datasette

You can confirm that the install worked using:

    $ datasette --version
    datasette, version 0.46

## Installing plugins

[Datasette plugins](https://datasette.readthedocs.io/en/stable/plugins.html) need to be installed into the same Python environment as `datasette`.

You can install plugins into the correct environment using the `pip` command at `/usr/local/opt/datasette/libexec/bin/pip` - for example:

    /usr/local/opt/datasette/libexec/bin/pip install datasette-vega

Run `datasette plugins` to see a list of currently installed plugins.
