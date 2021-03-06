[![MELPA](https://melpa.org/packages/sexy-monochrome-theme-badge.svg)](https://melpa.org/#/sexy-monochrome-theme)
# Sexy monochrome theme for emacs
This theme is based on the Xavier Noria [monochrome-theme](https://github.com/fxn/monochrome-theme.el).

And impressed by ["Monochrome color scheme for Vim"](https://github.com/fxn/vim-monochrome)

## Screenshots
### Source Code

![Sexy monochrome theme source code](https://raw.githubusercontent.com/nuncostans/sexy-monochrome-theme/master/sexy-monochrome-theme.png)


### Installation
Just install form MELPA

```elisp
     M-x package-install RET sexy-monochrome-theme RET
```
and then put in your init file

```elisp
     (load-theme 'sexy-monochrome)
```

 **OR** 
 _throw this file into ~/.emacs.d and_
 
```elisp
     (add-to-list 'custom-theme-load-path
                  "~/.emacs.d/YOUR_FOLDER_WITH_THEME/")
```
and

```elisp
     M-x load-theme RET sexy-monochrome RET
```
then put in your init file
```elisp
    (load-theme 'sexy-monochrome)
```

Works with Emacs >= 24.
