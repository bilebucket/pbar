# PBAR

## What is it?

pbar is a simple system status script written in python, and it's meant to be piped to [LemonBoys Bar](https://github.com/LemonBoy/bar)

## Why?

I made pbar for fun.

## Can I use it?

Sure! Go nuts with it! But a word of warning: there are a some dependencies:

  * [lemonbar](https://github.com/LemonBoy/bar)
  * [arrow](https://pypi.python.org/pypi/arrow/0.4.2)
  * [psutil](https://pypi.python.org/pypi/psutil)
  * [xdotool](http://www.semicomplete.com/projects/xdotool/)

Also I wrote the script very specifically for my own system configuration, so additional setup (e.g. cronjobs to write battery status to a file) might be needed. Oh, and the script can be quite error prone, plus I really don't know how I could optimize it. *Cough Cough! Pull requests*

### How do I use it?

  * Read the sources of pbar and bar.sh
  * install dependencies
  * Test run bar.sh
  * modify to your liking

If you actually try it and fix, modify, add something please, feel free to leave a pull request.
