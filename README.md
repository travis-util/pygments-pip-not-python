# pygments-pip-not-python
Shows usage of Pygments in Travis with language different from python and bad results on YAML files

[![Build Status](https://travis-ci.org/travis-util/pygments-pip-not-python.svg?branch=master)](https://travis-ci.org/travis-util/pygments-pip-not-python)

## YAML
Usable (yaml comment are different and visible) styles for Travis console:
* manni
 * -f 256
 * manni -f html -O full -P linenos=1 example.yaml | elinks -force-html -dump-color-mode 3 -dump
* perldoc -f 16m
* rainbow_dash -f 256

## References
* http://pygments.org/docs/formatters/
