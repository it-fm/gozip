# gozip
A simple library to compress and unzip a folder or file recursively

```
go get -v -u github.com/it-fm/gozip
```

Eaxample

```go
package main

import (
	"github.com/it-fm/gozip"
)

func main() {
    gozip.Zip("folderToZip", "folder.zip")
    gozip.Unzip("folder.zip", "./resultExtracted")
}
