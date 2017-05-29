# update-macports
05/2017 Thomas Karmann <thomas@krmnn.de>

## Description
This script will update MacPorts and its installed ports and write a log to the given destination and mail it to you.
For mail, see [Make a MacOS send mail over relay via built-in postfix](https://gist.github.com/krmnn/d96ff20c1f43eb517ce6db222368cd17)


## Crontab example (crontab -e), runs every 12 hours:

  0 */12 * * * /path/to/bin/upgrade-macports

