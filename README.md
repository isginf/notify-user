Usage: `notify-user <user|--all> [options]`

This script is a wrapper for notify-send to allow
to notify users as root and/or from a script.

The first argument defines the user name(s) to be notified
(or --all for logged in users). All other arguments get
passed trough (see [notify-send(1)](https://manpages.debian.org/stretch/libnotify-bin/notify-send.1.en.html)).
