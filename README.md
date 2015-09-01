# govdoext

[![Godoc](http://img.shields.io/badge/godoc-reference-blue.svg?style=flat)](https://godoc.org/github.com/shamsher31/govdoext)
[![Build Status](https://travis-ci.org/shamsher31/govdoext.svg)](https://travis-ci.org/shamsher31/govdoext)

List of Video file extensions for Go

### How to install
```go
go get github.com/shamsher31/govdoext
```

### How to use
```go
package main

import (
	"fmt"
	"github.com/shamsher31/govdoext"
)

func main() {
	fmt.Println(vdoext.Get())
}
```

### Why
This package is inspired by [video-extensions](https://www.npmjs.com/package/video-extensions) npm module.

### License
MIT © [Shamsher Ansari](https://github.com/shamsher31)
