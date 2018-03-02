# twhs

[![Build Status](https://travis-ci.org/suzuki-shin/twhs.svg?branch=master)](https://travis-ci.org/suzuki-shin/twhs)

## About ##

CLI twitter client. Inspired by Tw (http://shokai.github.io/tw/)

## Install ##
```
$ cabal update && cabal install twhs
```

## Example ##

```
# tweet
$ twhs Lunch now!
```
```
# get timeline only 50 lines
$ twhs -n 50
```
```
# get user timeline
$ twhs -u shin16s
```
```
# in reply to
$ twhs -r 123456 ok! let's go
```

## Options ##

```
  -r ID MESSAGE  --reply=ID MESSAGE  in reply to ID
  -R ID          --retweet=ID        retweet ID
  -u USER        --user=USER         show user timeline
  -l LIST        --list=LIST         show list statuses
  -m             --mention           show mention timeline
  -f ID          --fav=ID            fav to ID
  -s             --stream            streaming timeline
  -n NUM         --num=NUM           take NUM
  -h             --help              show help
```
