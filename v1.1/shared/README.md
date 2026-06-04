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

### Github actions
To make sure the shared asciidoc files are the latest in a Github action, you can use the following steps:
```yaml
- name: Checkout repository with submodules
  uses: actions/checkout@v4
  with:
    submodules: true
    fetch-depth: 0

- name: Update submodules to latest main
  run: |
    git submodule foreach --recursive git fetch origin
    git submodule foreach --recursive git checkout origin/main
```
