# layer
layers

   ;; List of configuration layers to load.
   dotspacemacs-configuration-layers
   '(protobuf
     (yaml :variables yaml-enable-lsp t)
     (go :variables go-backend 'lsp
         go-format-before-save t)
     javascript
     auto-completion
     better-defaults
     cscope
     dap
     (docker :variables docker-dockerfile-backend 'lsp)
     emacs-lisp
     floobits
     git
     helm
     html
     lsp
     markdown
     multiple-cursors
     org
     pdf
     (shell :variables
            shell-default-height 30
            shell-default-position 'bottom)
     (shell-scripts :variables shell-scripts-format-on-save t)
     spell-checking
     svelte
     syntax-checking
     systemd
     version-control
     themes-megapack
     (treemacs :variables treemacs-use-follow-mode 't)
     unicode-fonts
     xclipboard)
