=========
Changelog
=========

Unreleased
----------

* Add ``terminal`` argument to ``launch_editor()`` and ``guess_editor()``.
  Pass ``terminal=False`` to skip terminal editors, such as Vim, when they would take over the terminal of a web server.

  `PR #4 <https://github.com/adamchainz/launch-editor-py/pull/4>`__.

* Only pass the line and column as separate arguments to the ``LAUNCH_EDITOR`` command, not to other editors chosen while it’s set.

  `PR #5 <https://github.com/adamchainz/launch-editor-py/pull/5>`__.

1.0.0 (2026-10-29)
------------------

* Initial release, ported from `launch-editor <https://github.com/vitejs/launch-editor>`__ 2.14.2.
