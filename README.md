# homebrew-datasette

To install [Datasette](https://github.com/simonw/datasette) using Homebrew:

    brew tap simonw/datasette
    brew install datasette

This almost works... having done this you can run:

    $ /usr/local/Cellar/datasette/0.46/libexec/bin/datasette --version
    datasette, version 0.46

But it doesn't add `datasette` to your regular PATH.

Please help out in [issue #2](https://github.com/simonw/homebrew-datasette/issues/2) if you know how to fix this!
