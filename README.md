# pygments-pip-not-python
Shows usage of Pygments in Travis with language different from python and bad results on YAML files

[![Build Status](https://travis-ci.org/travis-util/pygments-pip-not-python.svg?branch=master)](https://travis-ci.org/travis-util/pygments-pip-not-python)

## YAML
Usable (yaml comment are different and visible) styles for Travis console:
* manni
  * background = **black**, beige comments, violet separator
    * 256
    * html -O full -P linenos=1 example.yaml | elinks -force-html -dump-color-mode 3 -dump
* lovelace -f html -O full -P linenos=1 example.yaml | elinks -force-html  -dump -dump-color-mode
  * background = white
    * 1
    * 4
* xcode -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* vim -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = **black**, blue (or understriked) comments, violet numbers
    * 1
    * 2
    * 4
* autumn -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* abap -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* vs -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* rrt -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = **black**, green comments
    * 1
    * 4
* native -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = **black**, turquoise comments, blue separator, green %, turquoise numbers, nice output
    * 1
    * 4
* perldoc
  * 16m
    * background = **black**, blue comments
  * html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
    * background = white
      * 1
      * 4
* tango -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* friendly -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* murphy -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* bw -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* rainbow_dash
  * 256
  * html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = black
    * 3
  * background = white
    * 1
    * 4
* algol_nu -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* trac -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* algol -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = white
    * 1
    * 4
* fruity -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump -dump-color-mode
  * background = **black**, beige comments, turquoise nubers, red %, nice
    * 1
    * 4

## References
* http://pygments.org/docs/formatters/
