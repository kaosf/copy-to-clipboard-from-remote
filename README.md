# Copy text to clipboard from server

## Environments

* Ubuntu 14.04 Desktop

I think available also on other Linux Distributions.

## Prerequisite

* Adding SSH public key on the server (for an authentication without a password)
* `~/.serverhostname` file on the client
* xsel `sudo apt-get install xsel`
* `~/.clipboard` file on the server

`.serverhostname` must contain only 1 line. It is used as `ssh _HERE_ ...`.

## Installation

Copy `copyfromserver` to a directory in `PATH`.

## Usage

Create `~/.clipboard` on the server and `~/.serverhostname` on the client. Then run `copyfromserver` on the client. The text in `.clipboard` is sent to the clipboard by xsel.

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (C) 2015 ka
