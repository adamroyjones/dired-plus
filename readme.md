# dired-plus
This is a public mirror of Drew Adams' `dired+` package for Emacs. The source
for this package is:

```
https://www.emacswiki.org/emacs/download/dired%2b.el
```

Updates to this mirror are done on a whim. This repository is current as of **2019-11-09**.

The purpose of this repository is to make it simpler for
[doom-emacs](https://github.com/hlissner/doom-emacs) to grab and install the
package, as it is neither on ELPA nor MELPA, and as the `emacsmirror/emacswiki.org`
repository is enormous.

The command to place in `packages.el` is:

```elisp
(package! dired+ :recipe (:host github :repo "docbiz/dired-plus"))
```
