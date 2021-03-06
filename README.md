# Watchdog

This script checks remote files. For example, you need
an always-fresh copy of some remote file and to be notified if there are
any changes. The script checks your files every 6 hours (by default) and
sends notifications via Mail.app.

## Preconditions

OS X Yosemite at least.

## Installation

1. Copy files.

  ```
  $ make install
  ```

2. Set directories, filenames, links and message recipients.

  ```
  $ make configuration
  ```

## Usage

The script should work automagically after you log in.
You can run the command below to make the script work without relogin.

```
$ make start
```

Plus you can check how OS X sees it.

```
$ make status
```
