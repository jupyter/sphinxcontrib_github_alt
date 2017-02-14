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
