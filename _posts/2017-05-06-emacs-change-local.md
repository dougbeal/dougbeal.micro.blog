---
layout: post
microblog: true
audio: 
date: 2017-05-06 16:27:38 -0700
guid: http://dougbeal.micro.blog/2017/05/06/emacs-change-local.html
---
Emacs -  Change local indent in a javascript file, when it conflicts with global indent
eval-expression [M-:]
(progn (make-local-variable 'js-indent-level) (setq js-indent-level 2))
#emacs #elisp
