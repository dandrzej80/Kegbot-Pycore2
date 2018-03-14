.. _pycore-changelog:

Changelog
=========

Version 1.2.1 (2015-01-27)
--------------------------

* Limit maximum number of failed event retries (issue #6)

Version 1.2.0 (2014-08-21)
--------------------------

* Automatically create a controller on the server when one is connected.
* Use 8-character kegboard names.

Version 1.1.3 (2014-06-26)
--------------------------

* Bugfix: Send kegboard device names.
* Fix dependencies for concurrent installs with ``kegbot-server``.

Version 1.1.2 (2014-04-14)
--------------------------

* Bugfix: Small pour detection.

Version 1.1.1 (2014-03-19)
--------------------------

* Improved error handling.
* Kegbot Server v0.9.18 (or later) is required.
* Fixes a bug introduced in v1.1.0 that could cause flow meter reports on an
  inactive kegboard.

Version 1.1.0 (2014-03-11)
--------------------------

* Pending pours are robustly retried.
* Internal: Redis is now required, replacing the internal "kegnet" protocol
  for event dispatching between daemons.

Version 1.0.2 (2012-10-30)
--------------------------

* Fixed a crash that occurred when starting kegbot_core.

Version 1.0.1 (2012-10-18)
--------------------------

* Fixed a crash when pouring with no keg bound to the tap.

Version 1.0.0 (2012-07-05)
--------------------------

* 1.0.0 release!
* Branched from `Kegbot server repository <https://github.com/Kegbot/kegbot/>`_.

Older version
-------------

Change history for older version can be found in the `Kegbot server repository
<https://github.com/Kegbot/kegbot/>`_.
