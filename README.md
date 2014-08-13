## Synopsis

Are you tired of using the endless keystrokes of <kbd>C-y M-y M-y M-y ...</kbd> to get
at that bit of text you killed thirty-seven kills ago? Ever wish you could just
look through everything you've killed recently to find out if you killed that
piece of text that you think you killed, but you're not quite sure? If so, then
`browse-kill-ring` is the Emacs extension for you.

## Installation

### Manual

Just drop `browse-kill-ring.el` somewhere in your `load-path`. The
folder `~/.emacs.d/vendor` is a popular choice:

```lisp
(add-to-list 'load-path "~/emacs.d/vendor")
(require 'browse-kill-ring)
```

### Marmalade

If you're an Emacs 24 user or you have a recent version of package.el
you can install browse-kill-ring from the [Marmalade](http://marmalade-repo.org/) repository.

### MELPA

If you're an Emacs 24 user or you have a recent version of package.el
you can install browse-kill-ring from the [MELPA](http://melpa.milkbox.net/) repository.

### el-get

If you prefer el-get, you can install browse-kill-ring with <kbd>M-x el-get-install</kbd>.

### Emacs Prelude

`browse-kill-ring` is naturally part of the
[Emacs Prelude](https://github.com/bbatsov/prelude). If you're a Prelude
user - `browse-kill-ring` is already properly configured and ready for
action.

## Usage

Just do `M-x browse-kill-ring`.

Optionally, you can map <kbd>M-y</kbd> to `browse-kill-ring` by adding the form
`(browse-kill-ring-default-keybindings)` to your `~/.emacs`.
Alternatively you can map `browse-kill-ring` to another key combination,
for example `(global-set-key "\C-cy" 'browse-kill-ring)`.

## Known issues

Check out the project's
[issue list](https://github.com/browse-kill-ring/browse-kill-ring/issues?sort=created&direction=desc&state=open)
a list of unresolved issues. By the way - feel free to fix any of them
and send a pull request. :-)

## History

Originally written by Colin Walters (Debian Developer, Emacs hacker, SELinux
hacker, and general Free Software Guru Extrordinaire). After that maintained
by [Nick Hurley](https://github.com/todesschaf). Unfortunately he had to abandon Emacs and this organisation
account was created at Github. Feel free to issue pull requests.

## Contributors

Here's a [list](https://github.com/browse-kill-ring/browse-kill-ring/contributors) of all the people who have contributed to the
development of browse-kill-ring.

## Bugs & Improvements

Bug reports and suggestions for improvements are always
welcome. GitHub pull requests are even better! :-)
