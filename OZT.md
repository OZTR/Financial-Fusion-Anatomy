---
NAME: "Fusion"
ABOUT: Harmonization of equations
UNIT: 'ETC'
TITLE: 'Speace'
LABEL: '17.009'
BLOCK: 2.71828182846

---
[![MacOS Build Status](https://circleci.com/gh/ethereumproject/go-ethereum/tree/master.svg?style=shield)](https://circleci.com/gh/ethereumproject/go-ethereum/tree/master)
[![Windows Build Status](https://ci.appveyor.com/api/projects/status/github/ethereumproject/go-ethereum?svg=true)](https://ci.appveyor.com/project/splix/go-ethereum)
[![Go Report Card](https://goreportcard.com/badge/github.com/ethereumproject/go-ethereum)](https://goreportcard.com/report/github.com/ethereumproject/go-ethereum)
[![API Reference](https://camo.githubusercontent.com/915b7be44ada53c290eb157634330494ebe3e30a/68747470733a2f2f676f646f632e6f72672f6769746875622e636f6d2f676f6c616e672f6764646f3f7374617475732e737667
)](https://godoc.org/github.com/ethereumproject/go-ethereum)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ethereumproject/go-ethereum?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# Financial-Fusion-Anatomy - FFA 

…or import code from another repository 
 #You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
 
```
$ go get -v github.com/ethereumproject/go-ethereum/...`
```

#### Install and build command executables

Executables installed from source will, by default, be installed in `$GOPATH/bin/`.

##### With go:

- the full suite of utilities:
```
$ go install github.com/ethereumproject/go-ethereum/cmd/...`
```

- just __geth__:
```
$ go install github.com/ethereumproject/go-ethereum/cmd/geth`
```

##### With make:
```
$ cd $GOPATH/src/github.com/ethereumproject/go-ethereum
```

- the full suite of utilities:
```
$ make install
```

- just __geth__:
```
$ make install_geth
```

> For further `make` information, use `make help` to see a list and description of available make
> commands.
