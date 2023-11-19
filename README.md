# Singularity recipe for [Quarto](https://quarto.org/)

How to fetch and use the image:
```
$ singularity pull https://github.com/bast/singularity-quarto/releases/download/0.3.0/quarto.sif

$ ./quarto.sif --help
$ ./quarto.sif preview document.md
$ ./quarto.sif render document.md
```

I have used this wonderful guide as starting point and inspiration:
https://github.com/singularityhub/singularity-deploy
