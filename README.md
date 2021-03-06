# cookiecutter-pypackage

This is a cookiecutter fork for those who want to use markdown for documenting.

Cookiecutter template for a Python package. See https://github.com/audreyr/cookiecutter.

* [Pytest](http://pytest.org/) runner: Supports `unittest`, `pytest`, `nose` style tests and more
* [TravisCI](http://travis-ci.org/) Ready for Travis Continuous integration testing
* [Tox](http://testrun.org/tox/) testing: Setup to easily test for python 2.6, 2.7, 3.3 and [PyPy](http://pypy.org/)
* [GitHub markdown](https://help.github.com/articles/github-flavored-markdown) as docs
* [Wheel](http://pythonwheels.com) support: Use the newest python package distribution standard from the get go

## Usage

Generate a Python package project::

    cookiecutter https://github.com/kimmobrunfeldt/cookiecutter-pypackage.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis CI account.
* Run `tox` to make sure all tests pass.
* Release your package the standard Python way.

## Not Exactly What You Want?

Don't worry, you have options:

### Original Cookiecutter Template

* [audreyr/cookiecutter](https://github.com/audreyr/cookiecutter): The original pypackage, uses unittest
for testing and other minor changes.

### Fork This

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Once you have your fork working, add it to the
Similar Cookiecutter Templates list with a brief explanation. It's up to you
whether or not to rename your fork.

### Or Submit a Pull Request

I also accept pull requests on this, if they're small, atomic, and if they
make my own packaging experience better.

## License

BSD
