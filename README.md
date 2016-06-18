# go-fmt-fail

`go fmt` fails when a file is formatted.

# Install

You can grab a pre-built binary file in the [releases page](https://github.com/mh-cbon/go-fmt-fail/releases)

```sh
mkdir -p $GOPATH/github.com/mh-cbon
cd $GOPATH/github.com/mh-cbon
git clone https://github.com/mh-cbon/go-fmt-fail.git
cd go-fmt-fail
glide install
go install
```

# Usage

```sh
go-fmt-fail [options] [packages]
```
