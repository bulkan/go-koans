# WARNING

This repo contains the solution to the go-koans !

## Go Koans

Teaches basic Go concepts and syntax by example.

### Usage

  1. Install Go with your favorite package manager or from [the official downloads link](http://code.google.com/p/go/downloads/list).
  2. Clone this repo.
  3. Run `go test`.
  4. Make the failing tests pass, by replacing these types of `__variables__` with real values.

#### Cooler usage

If you want to have `go test` be run in your terminal any time you save a file and
are using a Mac, take a look at [fswatch](http://github.com/sdegutis/fswatch).

### Helpful References

Bookmark the [spec](http://golang.org/ref/spec) and the
[packages listing](http://golang.org/pkg/). You can also
run the Go website locally with `godoc -http=:8080`.

### For Vim users

Add this to your `~/.vimrc` file:

```viml
set rtp+=/usr/local/opt/go/misc/vim
filetype plugin indent on
syntax on
```

### For Emacs users

```lisp
(add-to-list 'load-path "/usr/local/opt/go/misc/emacs" t)
(require 'go-mode-load)
```
