# Collect number of available apt updates for netdata

This plugin collects a number of currently available apt updates (from `apt-get` shell command)
this metric is missed from core netdata.

## Manual install
- copy plugin to `python.d` plugins dir
- copy config to `/etc/netdata/python.d/`
- restart netdata, check "apt updates" section

## Configuration
As usual, no config is required by default
- to disable plugin, set `command` to `/bin/false`
- to change check interval, set `update_every`

## Compatibility

Tested on Debian 8 - 11.