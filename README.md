# update-macports
20/05/2017 by Thomas Karmann <thomas@krmnn.de>

## Description
This script will update MacPorts and its installed ports and write a log to the given destination and mail it to you.
Just customize the env vars `LOG_DESTINATION` and `EMAIL` at the top of the script.

For a simple mail relay configuration, see [Make a MacOS send mail over relay via built-in postfix](https://gist.github.com/krmnn/d96ff20c1f43eb517ce6db222368cd17).


## Running it

e.g. by crontab (edit via `crontab -e`), every 12 hours:
```
    0 */12 * * * /path/to/bin/update-macports
```

