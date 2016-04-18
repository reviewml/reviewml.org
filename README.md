# Publish Your Books with Re:VIEW

Re:VIEW is an powerful and easy to use digital publishing sysytem for books and ebooks.

## Usage

```shell-session
$ gem install review
$ review-init my-awesome-book
$ cd my-awesome-book
$ (... edit files ...)
$ rake epub   ## generating EPUB
$ rake pdf    ## generating PDF
```

## Support Formats

Re:VIEW uses its original format ('Re:VIEW format') as source files.

Output formats Re:VIEW supports are:

* EPUB
* LaTeX (TeXLive)
* InDesign (IDGXML)
* plain text (TOPBuilder Text Markup Language)
* Markdown

## Project Site

https://github.com/kmuto/review

## License

LGPL. See COPYING file.

## Copyright

Copyright © 2006-2016 Minero Aoki, Kenshi Muto, Masayoshi Takahashi, Masanori Kado.
