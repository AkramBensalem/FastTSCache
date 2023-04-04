# FastTSCache

## Overview

FastTSCache is a faste time series in-memory cache based on Twitter's FatCach

## Build


To build FastTSCache from code source:

    $ git clone git@github.com:twitter/fatcache.git
    $ cd fatcache
    $ autoreconf -fvi
    $ ./configure --enable-debug=log
    $ make
    $ src/fatcache -h
