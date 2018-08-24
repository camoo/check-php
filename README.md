# check-php
check-php is a fast PHP synthax checker for developers
# Installation:
- clone the repo

`sudo cp -p check-php /usr/local/bin/check-php`

# Usage : check-php

# SYNOPSIS
  `check-php [--help| -h] [-s <DIR>] [-g <Yy|Nn>] [--force | -f]`

# DESCRIPTION
   check-php is a fast PHP synthax checker for developers
   Calling this without paramter will Check all PHP-files modified between now and 1 day ago

# OPTIONS
  `-f | --force`
  
  ignore nonexistent directory, never prompt
  
  `--help | -h`
  
  Prints the synopsis and a list of the most commonly used commands.
  
`-s | --sub-dir <DIR>`

Run as if check-php was started in <DIR> instead of the wohle project directory.
 
 `-g | --git-modified <Yy|Nn>`
 
 Check Only PHP-files modified in GIT if the value is yes (y|Y)
