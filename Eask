;; -*- mode: eask; lexical-binding: t -*-

(package "lua-mode"
         "20221027"
         "a major-mode for editing Lua scripts")

(website-url "https://immerrr.github.io/lua-mode")
(keywords "languages" "processes" "tools")

(package-file "lua-mode.el")
(files "lua-mode-*.el")

(script "test" "echo \"Error: no test specified\" && exit 1")

(source 'gnu)
(source 'melpa)

(depends-on "emacs" "26.1")

(development
 (depends-on "buttercup"))

(setq network-security-level 'low)  ; see https://github.com/jcs090218/setup-emacs-windows/issues/156#issuecomment-932956432
