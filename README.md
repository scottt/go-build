1. This script uses the system gc installation in `/usr` to ([bootstrap](https://golang.org/doc/install/source#go14)) Go from source
 1. e.g. Under Fedora, `dnf install -y gcc-go`
1. `git clone https://go.googlesource.com/go`
1. Set [GO-VERSION](GO-VERSION) file content to a string like `go1.11`
1. Run `./go-build`, `./go-install`
 1. Or `source go-build` to set `GOROOT_FINAL`, `GOROOT_BOOTSTRAP` in the interactive shell
