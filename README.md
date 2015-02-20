Overview [![Build Status](https://travis-ci.org/soutenniza/cf-plugin-open.svg?branch=help-error)](https://travis-ci.org/soutenniza/cf-plugin-open)
========

Open app url in browser

Installation
------------

```
$ go get github.com/cloudfoundry-community/cf-plugin-open
$ cf install-plugin $GOPATH/bin/open
```

Usage
-----

```
$ cf open <appname>
```

Development
-----------

```
cf uninstall-plugin open; go get ./...; cf install-plugin $GOPATH/bin/cf-plugin-open
```
