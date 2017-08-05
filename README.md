# Sample app for miso

Tested on NixOS. Per instructions from https://github.com/haskell-miso/miso#nix 

```
nix-build
open ./result/bin/app.jsexe/index.html
```

Launch web server to serve generated files:

```
warp -d result/bin/app.jsexe/
```
