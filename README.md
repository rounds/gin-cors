CORS middleware for [gin].

# DEPRECATED

This package is no longer maintained and will be removed in the future.
Please use the CORS subpackage in [rounds/go-gin-contrib][contrib] instead.

## Installation

``` bash
$ go get github.com/tommy351/gin-cors
```

## Use

``` go
import (
    "github.com/gin-gonic/gin"
    "github.com/tommy351/gin-cors"
)

func main(){
    g := gin.New()
    g.Use(cors.Middleware(cors.Options{}))
}
```

[gin]: http://gin-gonic.github.io/gin/
[contrib]: https://github.com/rounds/go-gin-contrib
