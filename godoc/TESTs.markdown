# example
--
    import "command-line-arguments"

This is the package comment, a top-level piece of documentation used to explain
things about the package (see json or exp/template) All godoc comments are in
this form with no whitespace between them and what they accompany

## Usage

```go
const (
	CONSTA = iota
	CONSTB
	CONSTC
	CONSTD
	ANOTHER = 7
)
```
Some enum examples

```go
var Default float64 = 0.7
```
This is just a random variable

#### type Example

```go
type Example float64
```

Example is a float used for demonstration purposes

#### func (Example) Sqrt

```go
func (e Example) Sqrt() Example
```
Returns the square root of an example

#### type Example2

```go
type Example2 struct {
	X Example
}
```

Example2 is also for demonstartion

#### func  NewExample

```go
func NewExample(num int) *Example2
```
NewExample is used to get a ready-to-use Example2
