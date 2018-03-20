# Youthweb Support Center

Hier liegt die Documentation von Youthweb ab.

## Requirements


* Python
* Sphinx

    sudo apt install python3-sphinx

## HTML generieren

Unter Unix:

make -C _build/ html

Unter Windows:

```
_build/make.bat html
```

### Update current version

    rm -r docs/current
    cp -r _build/html/ docs/current
    git add -A
    git commit -m 'Update current version'
