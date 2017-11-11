# Calender for Golang

Output HTML and Markdown calender.

## Usage

```go
package main

import (
	"fmt"
	"github.com/binzume/go-calender"
)

func main() {
	fmt.Println(calender.NewCalender().Markdown())
}
```

### Output example

```
| Sun | Mon | Tue | Wed | Thu | Fri | Sat |
|----:|----:|----:|----:|----:|----:|----:|
|     |     |     |   1 |   2 |   3 |   4 |
|   5 |   6 |   7 |   8 |   9 |  10 |  11 |
|  12 |  13 |  14 |  15 |  16 |  17 |  18 |
|  19 |  20 |  21 |  22 |  23 |  24 |  25 |
|  26 |  27 |  28 |  29 |  30 |     |     |
```

| Sun | Mon | Tue | Wed | Thu | Fri | Sat |
|----:|----:|----:|----:|----:|----:|----:|
|     |     |     |   1 |   2 |   3 |   4 |
|   5 |   6 |   7 |   8 |   9 |  10 |  11 |
|  12 |  13 |  14 |  15 |  16 |  17 |  18 |
|  19 |  20 |  21 |  22 |  23 |  24 |  25 |
|  26 |  27 |  28 |  29 |  30 |     |     |

# License

These codes are licensed under CC0.

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)
