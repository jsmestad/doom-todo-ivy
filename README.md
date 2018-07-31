# doom-todo-ivy
Display TODO, FIXME, or anything else in an ivy buffer. Extracted from doom-emacs.

## Install

This package depends on:

* ivy
* projectile

### Manual

```lisp
(require 'doom-todo-ivy)
```

### use-package

```lisp
(use-package doom-todo-ivy
  :ensure t
  :hook (after-init . doom-todo-ivy))
```

You can run the command with `M-: doom/ivy-tasks [RET]`

## Demo

![todo](https://raw.githubusercontent.com/hlissner/doom-emacs/screenshots/modules/completion/ivy/ivy-todo.gif)
