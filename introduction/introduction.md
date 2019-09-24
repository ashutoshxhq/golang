# Introduction of GOLANG

Go is a procedural programming language. It was developed in 2007 by Robert Griesemer, Rob Pike, and Ken Thompson at Google but launched in 2009 as an open-source programming language. Programs are assembled by using packages, for efficient management of dependencies. This language also supports environment adopting patterns alike to dynamic languages. For eg., type inference (y := 0 is a valid declaration of a variable y of type float).

## What do you need to run go?
* GO compiler
* Code Editor(eg: Code,VIM,Emacs,notepad etc)

## What does the hello world look like?
```
package main  
 
import "fmt"

func main() {

     // prints Hello World
     fmt.Println("Hello World") 
}
```

## How do you compile and run it?
Save the code as filename.go and
To just compile and build the binary
```
$ go build filename.go
```
OR
To compile and build the binary and also run it
```
$ go run filename.go
```

## Want to understand the code?
* Line 1: In this line,we name the package as main which is considered as entry package of any go app
* Line 2: In this line, we import the fmt package which tells the compiler to include the files lying in the package.
* Line 3: