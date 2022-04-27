# cooklang-micro

[Cooklang][1] syntax highlighting for the [micro][2] editor.

---

## :gear:&nbsp; Usage

> :warning: Warning: This repo is still a work in progress

### Copy to Location

Copy `cook.yaml` to the `~/.config/micro/syntax/` folder.

### Symbolic Link from Repo

Make a symbolic link from the repo directory if you want to keep the syntax file up to date.

```shell
# Create the syntax directory if it doesn't exist
mkdir -p ~/.config/micro/syntax
# From repository folder
ln -sr ./syntax/cook.yaml $HOME/.config/micro/syntax/cook.yaml
# Check that it was successfully created
ls ~/.config/micro/syntax/
```

---

## ​:balance_scale:&nbsp;​ License

​[​Apache License 2.0](./LICENSE)

---

## ​:pencil:&nbsp;​ Author

​This project was started in 2022 by [​Nicholas Wilde​](https://github.com/nicholaswilde/).

[1]: https://cooklang.org/
[2]: https://micro-editor.github.io/
