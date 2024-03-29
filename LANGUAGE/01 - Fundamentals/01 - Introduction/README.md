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

## Lets understand the code
* Line 1: In this line,we name the package as main which is considered as entry package of any go app.
* Line 2: In this line, we import the fmt package which tells the compiler to include the files lying in the package.
* Line 3: In this line, we create a function called main which is the entry point of the program.
* Line 4: In this line, we used a library funtion called Println from the fmt library to print something on the screen.

## How do you compile and run it?
Save the code as filename.go and <br>
To compile and build the binary run: 
```
$ go build filename.go
```
Or to compile, build and also run it execute:
```
$ go run filename.go
```

**NOTE: All Commands are to be executed in terminal/cmd**

## Why use go ?
Because Go language is an effort to combine the ease of programming of an interpreted, dynamically typed language with the efficiency and safety of a statically typed, compiled language. It also aims to be modern, with support for networked and multicore computing.

## Advantages and Disadvantages of Go Language

**Advantages**
* Flexible- It is concise, simple and easy to read.
* Concurrency- It allows multiple process running simultaneously and effectively.
* Quick Outcome- Its compilation time is very fast.
* Library- It provide a rich standard library.
* Garbage collection- It is a key feature of go. Go excels in giving a lot of control over memory allocation and has dramatically reduced latency in the most recent versions of the garbage collector.
* It validates for the interface and type embedding.

**Disadvantages**
* It has no support for generics, even if there are many discussions about it.
* The packages distributed with this programming language is quite useful but Go is not so object-oriented in the conventional sense.
* There is absence of some libraries especially a UI tool kit.

## Things build with go
* Docker: a set of tools for deploying linux containers
* Openshift: a cloud computing platform as a service by Red Hat.
* Kubernetes: The future of seamlessly automated deployment processes
* Dropbox: migrated some of their critical components from Python to Go.
* Netflix: for two part of their server architecture.
* InfluxDB: is an open-source time series database developed by InfluxData.