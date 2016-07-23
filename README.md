# go-fmt-fail

`go fmt` fails when a file is formatted.

## Install

Pick an msi package [here](https://github.com/mh-cbon/go-fmt-fail/releases)!

__deb/rpm__

```sh
curl -L https://raw.githubusercontent.com/mh-cbon/latest/master/install.sh \
| GH=mh-cbon/go-fmt-fail sh -xe
# or
wget -q -O - --no-check-certificate \
https://raw.githubusercontent.com/mh-cbon/latest/master/install.sh \
| GH=mh-cbon/go-fmt-fail sh -xe
```

__go__

```sh
mkdir -p $GOPATH/src/github.com/mh-cbon
cd $GOPATH/src/github.com/mh-cbon
git clone https://github.com/mh-cbon/go-fmt-fail.git
cd go-fmt-fail
glide install
go install
```

# Usage

```sh
go-fmt-fail [packages or files]
```
