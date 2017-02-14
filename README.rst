Link to GitHub issues, pull requests, commits and users for a particular project.

To use this extension, add it to the ``extensions`` list in ``conf.py``,
and set the variable ``github_project_url``:

.. code-block:: python

    extensions = [...
                  'sphinxcontrib_github_alt',
                 ]

    github_project_url = "https://github.com/ipython/ipython"

Then use these roles in your documentation:

.. code-block:: rst

    * :ghissue:`12` - link to issue #12
    * :ghpull:`35` - link to pull request #35
    * :ghcommit:`3a1cb54` - link to commit
    * :ghuser:`ipython` - link to a user or organisation


It's called 'alt' because `sphinxcontrib-github
<https://pypi.python.org/pypi/sphinxcontrib-github/>`__ already exists. IPython
& Jupyter projects have been using the syntax defined in this extension for some
time before we made it into its own package, so we didn't want to switch to
``sphinxcontrib-github``.
