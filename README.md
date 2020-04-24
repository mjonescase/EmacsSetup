# EmacsSetup
Files and instructions to duplicate my local Emacs setup.

Steps to install

- OSX: `brew install emacs`

Steps to set up

- copy `.emacs` into your home directory, as a file named `.emacs`.
- open Emacs. Run these commands to install two `el-get` libraries:

```
M-x el-get-install <RET> yafolding <RET>
M-x el-get-install <RET> auto-complete <RET>
M-x el-get-install <RET> typescript-mode <RET>
```

- open SeitiZenitaniDotEmacs in emacs. Run `M-x byte-compile-file`, and select this file when prompted. This will generate the file `SeijiZenitaniDotEmacs.elc`. Move this file to the directory ~/lib/emacs (create it if it doesn't already exist).

- open PowerShellMode.el in emacs. Run `M-x byte-compile-file`, and select this file when prompted. This will generate the file `PowerShellMode.elc`. Move this file to the directory ~/lib/emacs.


- Close emacs and re-open it.