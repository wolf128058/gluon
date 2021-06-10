[![Build Gluon](https://github.com/freifunk-gluon/gluon/actions/workflows/build-gluon.yml/badge.svg?branch=master)](https://github.com/freifunk-gluon/gluon/actions/workflows/build-gluon.yml)
[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/freifunk-gluon/gluon?sort=semver)](https://github.com/freifunk-gluon/gluon/releases/latest)

Documentation (incomplete at this time, contribute if you can!) may be found at
https://gluon.readthedocs.io/.

If you're new to Gluon and ready to get your feet wet, have a look at the
[Getting Started Guide](https://gluon.readthedocs.io/en/latest/user/getting_started.html).

Gluon's developers frequent an IRC chatroom at [#gluon](ircs://irc.hackint.org/#gluon)
on [hackint](https://hackint.org/). There is also a [webchat](https://webirc.hackint.org/#irc://irc.hackint.org/#gluon)
that allows for access from within your browser.

## Issues & Feature requests

Before opening an issue, make sure to check whether any existing issues
(open or closed) match. If you're suggesting a new feature, drop by on IRC or
our mailinglist to discuss it first.

We maintain a [Roadmap](https://github.com/freifunk-gluon/gluon/wiki/Roadmap) for
the future development of Gluon.

## Use a release!

Please refrain from using the `master` branch for anything else but development purposes!
Use the most recent release instead. You can list all releases by running `git tag`
and switch to one by running `git checkout v2021.1 && make update`.

If you're using the autoupdater, do not autoupdate nodes with anything but releases.
If you upgrade using random master commits the nodes *will break* eventually.

## Mailinglist

To subscribe to the list, send a message to:

    gluon+subscribe@luebeck.freifunk.net

To remove your address from the list, just send a message to
the address in the `List-Unsubscribe` header of any list
message. If you haven't changed addresses since subscribing,
you can also send a message to:

    gluon+unsubscribe@luebeck.freifunk.net
