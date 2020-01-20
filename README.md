# standardcfg

Bash library containing lots of hacks clamped together over time.

## Features
When script A uses this library, i can:
- Automatically run A in a terminal if not opened in such
- Change working directory to where the script A is located in
- Allow event handling
- Automatic argument parsing
- Make sure only one instance of script A is running
- Access to lots of functions

## Usage

1. Add this script to $PATH
2. Simply put ```$(standardcfg)``` on top of your bash script, but after ```#!/bin/bash ```
