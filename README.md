# Copy text to clipboard from remote

## Environments

* Ubuntu 14.04 Desktop

I think available also on other Linux Distributions.

## Prerequisite

* Adding SSH public key on the remote (for an authentication without a password)
* `~/.remotehostname` file on the local
* xsel `sudo apt-get install xsel`
* `~/.clipboard` file on the remote

`.remotehostname` must contain only 1 line. It is used as `ssh _HERE_ ...`.

## Installation

Copy `copyfromremote` to a directory in `PATH`.

## Usage

Create `~/.clipboard` on the remote and `~/.remotehostname` on the local. Then run `copyfromremote` on the local. The text in `.clipboard` is sent to the clipboard by xsel.

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (C) 2015 ka
