dprint pre-commit mirror
========================

Mirror of `dprint <https://dprint.dev/>`__ for `pre-commit <https://pre-commit.com>`__.

Installation
------------

Add to your pre-commit config:

.. code-block:: yaml

    -   repo: https://github.com/adamchainz/pre-commit-dprint
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: dprint

You’ll also need a `dprint configuration file <https://dprint.dev/config/>`__ in the root of your repository.
