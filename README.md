# go-pry

go-pry is an interactive REPL for Go that allows you to drop into your code at any point.


## Usage
Install go-pry
```bash
go get github.com/d4l3k/go-pry
go install github.com/d4l3k/go-pry

```

Add the pry statement to the code
```go
import "github.com/d4l3k/go-pry/pry"

...

func main() {
  a : = 1
  pry.Pry()
}
```

Run the code
```bash
# Run
go-pry <go file>
```


## License

go-pry is licensed under the MIT license.
