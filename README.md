
install
-------

First download css/js files:

``` bash
cd .cabal/share/gitit-0.9/data/static/css

# download bootstrap.css
wget http://bootswatch.com/assets/css/bootstrap.css
mv screen.css screen.css.bak  # backup screen.css
mv bootstrap.css screen.css

cd ../js
wget https://raw.github.com/humiaozuzu/gitit-bootstrappifier/master/gitit-bootstrap.js

# goto template dir
cd ../../templates
```

Then, let every page of gitit include gitit-bootstrap.js

just add `<script src="/js/gitit-bootstrap.js" type="text/javascript"></script>` in file `page.st` after line `$javascripts$`

sceenshot
---------

![demo](https://github.com/humiaozuzu/gitit-bootstrappifier/raw/master/demo.png)
