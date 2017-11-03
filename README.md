# Name

*notify-user* - A wrapper for Debians *notify-send* program

# Synopsis

`notify-user (user|--all|--help) [...]`

# Description

This script is a wrapper for *notify-send* to allow
to notify users as root and/or from a script. It solves
the issue that *notify-send* requires a valid value of
*DBUS_SESSION_BUS_ADDRESS* which is only available in
the graphical session of the user.

# Options

The first argument defines who receives the notification.
*--all* will sends it to logged in users. Alternatively,
a user name or a space separated list of user names can
be provided.

*--help* displays a short help.

All further arguments will be passed to *notify-send*.

# See also

- [notify-send(1)](https://manpages.debian.org/stretch/libnotify-bin/notify-send.1.en.html)

# Compatibility

The script was tested on:

- Ubuntu 16.04
- Ubuntu 17.04
- Ubuntu 17.10
- Red Hat Enterprise Linux 7
- Fedora 26

# Author

Copyright 2017 ETH Zurich, D-INFK ISG, Manuel Mästinger

- Email: manuel.maestinger@inf.ethz.ch
- Web: https://www.isg.inf.ethz.ch
