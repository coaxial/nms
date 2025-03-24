# nms (notmuch search)

This is a utility to show the `notmuch search` results in a more readable way.
It can then open the chosen message in Evolution Mail.

This script was 99% written by Claude AI (via aider.chat).

## Usage

`$ nms "search string"` will then load the results in a TUI (with vim bindings).

## Debugging

Set the `NMS_DEBUG` environment variable to `1` to enable debug logging: `$ NMS_DEBUG=1 nms "search string"`. Log files are at `~/.nms_*debug.log`.

## Installation

`$ cp nms ~/.local/bin/nms` (make sure `~/.local/bin` is in your `$PATH`)
