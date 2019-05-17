#  Centrifuge Protocol Yellow Paper
To read the latest PDF version of the paper, check out the [releases on github](https://github.com/centrifuge/protocol/releases)

## Building 
The easiest way to generate a PDF out of the tex file is with docker:

```
docker run --rm -i --user="$(id -u):$(id -g)" --net=none -v "$PWD":/data "blang/latex:ctanfull" latexmk -pdf -outdir=./build
```

