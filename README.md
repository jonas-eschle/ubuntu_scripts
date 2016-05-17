# README ubuntu_scrpts #

## What is it? ##

This repository contains several small, but useful scripts regarding Ubuntu.
They are mostly written in, but not limited to, bash.

All information for the scripts are collected in this readme.

## Available scripts ##

- [clean_cache.sh](#clean_cache.sh): Bash; cleans the cache (which is not operation-critical) of the system


## Scripts explained ##

### clean_cache.sh ###

Useful if used in a GUI. To run it, for example in GNOME, use:
> gksu bash /path-to-script/clean_cache.sh

Where gksu is the *sudo* which prompts in an extra window for your password.
Should be used for any GUI application that uses sudo.
