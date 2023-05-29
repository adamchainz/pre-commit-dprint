dprint pre-commit mirror
========================

----

**Unmaintained:** I'm no longer maintaining this repository because it doesn’t work very well with changes to dprint.
See `Issue #3 <https://github.com/adamchainz/pre-commit-dprint/issues/3>`__ and `Issue #4 <https://github.com/adamchainz/pre-commit-dprint/issues/4>`__.
If you’d like to take over, please email me.

----

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
