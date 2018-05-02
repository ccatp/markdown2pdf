# markdown2pdf

Usage:

```sh
./markdown2pdf filename.md
```

## Requirements

*Note: these are provided by the ['ccatp-dev' vagrant image](https://github.com/ccatp/os-images).*

On Ubuntu 18.04 LTS, the following packages are required:

```
pandoc
texlive-xetex
```

Optionally, if you want to embed diagrams you'll need:

```
graphviz
python3-pip
```

and then run the command `$ pip3 install panflute`.
