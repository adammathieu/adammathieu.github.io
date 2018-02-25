#Go

## What I encounter learning Go

### Import your first personal package

```sh
.\main.go:8:2: cannot refer to unexported name hello.sayHi
```
Indeed, create a package is not enough. How to export your function?
I was not obvious, but function or variable with Capital letter are global.
That's it. A capital letter and the function is exported.

