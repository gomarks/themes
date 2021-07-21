# GoAdmin Official Themes

- [adminlte](https://github.com/gomarks/themes/tree/master/adminlte)
- [sword](https://github.com/gomarks/themes/tree/master/sword)

[中文介绍](./README_CN.md)

## How to use

- Import the theme
- Set in the global configuration of GoAdmin

```go

package main

import (
	...
	_ "github.com/gomarks/themes/bjca"
	...
)

func main()  {
	
	...
	
	cfg := config.Config{
    		...
    		
    		Theme: "bjca",
    		
    		...
    	}
	
	...
 
}

```

## How to modify and make it work

Use the Makefile under each theme directory.