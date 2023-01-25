```terminal
$ nix build .#go-hello
warning: Git tree '/home/gianarb/git/test-go' is dirty
error: builder for '/nix/store/7prpq3mrmcz6mzhd3mzsmwkry84p2xcg-go-hello-20230125-go-modules.drv' failed with exit code 1;
       last 7 log lines:
       > unpacking sources
       > unpacking source archive /nix/store/p2jah5i8alkrmsyj7a96bqbzvhzn86w7-go
       > source root is go
       > patching sources
       > configuring
       > building
       > $GOPATH/go.mod exists but should not
       For full logs, run 'nix log /nix/store/7prpq3mrmcz6mzhd3mzsmwkry84p2xcg-go-hello-20230125-go-modules.drv'.
error: 1 dependencies of derivation '/nix/store/1l27cvxggvrlqwcvrfx4hzz9f74ksxq8-go-hello-20230125.drv' failed to build
```
