# Syntax highlighting for the B language


## Build a .vsix package

```bash
$ docker run -it --rm -v$PWD:/tmp -w/tmp node:alpine sh
$ yarn global add vsce
$ vsce package
```
