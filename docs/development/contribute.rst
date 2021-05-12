.. -*- coding: utf-8 -*-

==============
 Contributing
==============

.. _bug reports, feedback:

Bug reports, feedback
---------------------

You found a bug? Perfect, less to find for me!

Please take the time to check if it is already in the issue tracker at
https://github.com/BennyTheSen/ToDoListGenerator/issues

If you cannot find it in the tracker, create a new issue there.

.. _repository:

Repository
----------

The project is developed using the git_ distributed version control system.

You can clone Pylint and its dependencies from ::

  git clone https://github.com/BennyTheSen/ToDoListGenerator.git

.. _git: https://git-scm.com/

Got a change for the project?  Below are a few steps you should take to make sure
your patch gets accepted.

- Test your code

  * The project is currently not very well tested, with a low code coverage.
    It has two types of tests, usual unittests and integration tests.

    The documentation to tests can be found here:
    https://cookiecutter-django.readthedocs.io/en/latest/testing.html

- Add a short entry to the ChangeLog describing the change, except for internal
  implementation only changes. Not usually required, but for changes other than small
  bugs we also add a couple of sentences in the release document for that release,
  (`What's New` section). For the release document we usually write some more details,
  and it is also a good place to offer examples on how the new change is supposed to work.

- Add yourself to the `CONTRIBUTORS` file, flag yourself appropriately
  (if in doubt, you're a ``contributor``).

- Write a comprehensive commit message

- Relate your change to an issue in the tracker if such an issue exists (see
  https://docs.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue of the GitHub documentation for more
  information on this)

- Document your change, if it is a non-trivial one.

- Send a pull request from GitHub (see https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests for more insight
  about this topic)


Tips for Getting Started with Development
------------------------------------------------
* Ask me! -BennyTheSen

* When fixing a bug for a specific check, search the code for the warning
  message to find where the warning is raised,
  and therefore where the logic for that code exists.
