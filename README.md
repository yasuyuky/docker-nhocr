Docker Image for NHocr
======================

[NHocr is a command line OCR (Optical Character Recognition) program for Japanese language, etc.](https://osdn.jp/projects/nhocr/)


Usage
=====

Change directory to your image directory.

Then you enter into docker image.

```
docker run -it --rm -v ${PWD}:/images yasuyuky/nhocr
```

and a following command works

```
nhocr -block -o - source.pgm
```

License
=======
MIT
