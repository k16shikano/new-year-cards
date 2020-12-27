Although the resulting pdf file is a rather boring new year's card, `2021.ps` turns out to be a postscript quine. That is;

```bash
$ ps2pdf 2021.ps 2> result.ps 
$ diff 2021.ps result.ps 
$ # no difference!
```
