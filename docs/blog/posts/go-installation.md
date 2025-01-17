---
date:
  created: 2025-01-14
readtime: 15
links:
  - Homepage: index.md
  - Blog index: blog/index.md
  - External links:
    - Material documentation: https://squidfunk.github.io/mkdocs-material
categories:
  - Holidays
authors:
  - eddshared
---

# let's Go! REST API lambda

Here it is my first post, let's set up our development env.
<!-- more -->

# let's Go! REST API lambda

## Install

Let's go to the offical web site to install go in our computer and follow the instruction. [Download and install](https://go.dev/doc/install){:target="_blank"}

I am istalling in it in MacOs and I will be using [brew](https://formulae.brew.sh/formula/go){:target="_blank"}.

```cmd
brew install go
.
.
.
>go version 
go version go1.23.4 darwin/arm64
```

## Create a project

Go to your project folder. I like to have mine under my personal directory (mkdir ~/projects/go)

// create folder
```cmd
mkdir first
```
// change directory
```cmd
cd first
```
// init your project
```cmd
go mod init first
```
// create a new file
```cmd
touch first.go
```
// add the code

```cmd
package main

import (
	"fmt"
)

func main() {
	fmt.Println("Hello, world!")
}
// run your code
go run .
Hello, world!
```