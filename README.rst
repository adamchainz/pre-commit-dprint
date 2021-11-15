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

Then add a ``dprint.json`` (or ``.dprint.json``) `configuration file <https://dprint.dev/config/>`__ in the root of your repository.

By default all text files are passed to dprint, which then only acts on files for which it has a relevant plugin configured.
