## 0.9.19 (08/27/2015)

FEATURES

* Add SSH host and key exchange algorithm parameters (GH-8).

IMPROVEMENTS

* Fix various linting issues in manifests (GH-9).
* Validate SSH parameters (GH-8).
* Upgrade to Git 2.5.0 on windows platforms (GH-7).
* Enable `source` parameter for all `sys::iptables` protocol classes.
* `sys::apt::sources` is now an ensurable resource.
* `sys::inifile` improvements (GH-6).

BUG FIXES

* Ed22519 host keys are actually supported on Ubuntu 14 / Debian 7 on up.

## 0.9.18 (05/08/2015)

FEATURES:

* Add `sys::openbsd::disk` defined type for partioning and formatting OpenBSD
  disk devices.

IMPROVEMENTS:

* Add support for pflow devices to `sys::openbsd::interface`.
* Clean up `sys::ssh::config` and `sys::ssh::service`.
* Use native service resources for SSH on OpenBSD 5.7+.

BUG FIXES:

* Fix `sys::screen` package parameters for OpenBSD 5.7.

## 0.9.17 (04/08/2015)

IMPROVEMENTS:

* Updates for OpenBSD manifests (GH-4)

BUG FIXES:

* SELinux template location fix from Bill Weiss (GH-5)