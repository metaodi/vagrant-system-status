# Installation

1. Clone this repository
2. Make sure the two scripts `vagrant-status` and `vagrant-cache` are in your PATH
3. Setup a cronjob to keep the cache up to date (see below)

## Crontab entry

```
*/15 * * * * $HOME/bin/vagrant-cache -f
```

## Limits

Currently only virtualbox-based vagrant boxes are displayed, this is totally tailored for my needs.
If you need something else, consider to contribute.
