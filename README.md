# CateGOry practice

Practice challenges from `Category Theory for Programmers' by Bartosz Milewski.

Built with the proposed Go generics as per <https://blog.golang.org/generics-next-step>.

Usage as per <https://go.googlesource.com/go/+/refs/heads/dev.go2go/README.go2go.md> and `go doc cmd/go2go`.

## Golang

Install the custom Go toolchain:

	git clone https://github.com/golang/go/
	git checkout dev.go2go
	cd go/src
	./all.bash
	# Set $GO2PATH as per GO2PATH=$GOROOT/src/cmd/go2go/testdata/go2pat
	# Set $GOROOT to be the root of the repository as-needed

I install this as `go2`.

## Building/running programs

	go2 tool go2go run x.go2

## Examples

	; go2 tool go2go run identity.go2
	6 foo 3.141592653589793
	;
