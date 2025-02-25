# asciidoc-shared

This repository contains shared asciidoc files and is used as a git submodule.

## Add this repository as a submodule to the main repository
```shell
git submodule add https://github.com/Informasjonsforvaltning/asciidoc-shared.git <path/to/subfolder>
```

## Cloning a Repository with Submodules
If you are cloning a repository, you need to initialize the submodules:
```shell
git clone --recurse-submodules <your-main-repo-url>
````

If the repository is already cloned without submodules, you can initialize them using:
```shell
git submodule update --init --recursive
```
