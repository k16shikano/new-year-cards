# New Year Cards in PostScript 

In order to use `ps2pdf`, you need to set `-dNOSAFER` option because some scripts requires to `run` other script files.

```shell
> ps2pdf -dNOSAFER ****.ps
```

Or, you can use `gs` with `-sDEVICE=pdfwrite`.

```shell
> gs -q -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile=****.pdf ****.ps
```

## gallery

<img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2020/fileout.png" width="150"> <img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2021/2021.png" width="150"> 

<img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2018/2018.png" width="150"> <img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2017/2017.png" width="150">  <img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2016/2016.png" width="150"> <img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2015/2015.png" width="150"> <img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2014/2014.png" width="150">

<img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2013/2013.png" width="150"> <img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2012/2012.png" width="150"> <img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2011/2011.png" width="150"> <img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2010/2010.png" width="150"> <img src="https://raw.githubusercontent.com/k16shikano/new-year-cards/master/2008/2008.png" width="150">
