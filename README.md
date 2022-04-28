# cooklang-micro

[Cooklang][1] syntax highlighting for the [micro][2] editor.

---

## :gear:&nbsp; Usage

> :warning: Warning: This repo is still a work in progress

### :fax:&nbsp; Copy to Location

Copy `cook.yaml` to the `~/.config/micro/syntax/` folder.

```shell
# Create the syntax directory if it doesn't exist
mkdir -p ~/.config/micro/syntax
# From the repo directory
cp ./syntax/cook.yaml ~/.config/micro/syntax/
```

### :link:&nbsp; Symbolic Link from Repo

Make a symbolic link from the repo directory if you want to keep the syntax
file up to date.

```shell
# Create the syntax directory if it doesn't exist
mkdir -p ~/.config/micro/syntax
# From repo directory
ln -sr ./syntax/cook.yaml $HOME/.config/micro/syntax/cook.yaml
# Check that it was successfully created
ls ~/.config/micro/syntax/
```

---

## ​:balance_scale:&nbsp;​ License

​[​Apache License 2.0](./LICENSE)

---

## ​:pencil:&nbsp;​ Author

​This project was started in 2022 by [​Nicholas Wilde​][3].

[1]: https://cooklang.org/
[2]: https://micro-editor.github.io/
[3]: https://github.com/nicholaswilde/
