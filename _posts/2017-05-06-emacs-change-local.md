---
layout: post
date: 2017-05-06 23:27
---
Emacs -  Change local indent in a javascript file, when it conflicts with global indent
eval-expression [M-:]
(progn (make-local-variable 'js-indent-level) (setq js-indent-level 2))
#emacs #elisp
