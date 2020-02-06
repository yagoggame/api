# api

**Api** is a part of **yagogame**. 
**Yagogame** - is yet another Go game on the Go, made just for fun.

**Api** implements a protobuf api of **grpc_server**.

## Installation

To install this package, you need to install Go and setup your Go workspace on your computer. The simplest way to install the library is to run:

`$ go get -u github.com/yagoggame/api`

With Go module support (Go 1.11+), simply import `google.golang.org/grpc` in your source code and `go [build|run|test]` will automatically download the necessary dependencies 
[Go modules ref](https://github.com/golang/go/wiki/Modules).

## Contribution

Any modification in *api.proto* file should be followed by run of

`$ go generate`

to modify a module.

## License

The **Api** is part of **yagogame**.

yagogame is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

yagogame is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with yagogame.  If not, see <https://www.gnu.org/licenses/>.
