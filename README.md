# evil-tutor-ja
[![MELPA](https://melpa.org/packages/evil-tutor-ja-badge.svg)](https://melpa.org/#/evil-tutor-ja)

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc/generate-toc again -->
**Table of Contents**

- [evil-tutor-ja](#evil-tutor-ja)
    - [Description](#description)
    - [Quick start](#quick-start)
    - [Install](#install)
        - [Package manager](#package-manager)
        - [Manually](#manually)
    - [Acknowledgement](#acknowledgement)

<!-- markdown-toc end -->

## Description

Japanese Vimtutor adapted for Evil and wrapped in a major mode.

Features:
- restore last working file
- fast navigation between lessons with `C-j` and `C-k`

## Quick start

    M-x evil-tutor-ja-start

This will create a working file in `evil-tutor-working-ja-directory` (defaults
to `~/.emacs.d/.tutor-ja`)

## Install

### Package manager

You can either install `evil-tutor-ja` from [MELPA](https://melpa.org/#/evil-tutor-ja):

```
 M-x package-install evil-tutor-ja
```

### Manually

Add `evil-tutor-ja.el` to your load path. `evil-tutor-ja` requires `evil` and `evil-tutor` to be installed.

## Acknowledgement

This package is forked from [evil-tutor](https://github.com/syl20bnr/evil-tutor/blob/master/README.md).

