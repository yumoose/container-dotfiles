# container-dotfiles 🛠

Simple Dotfiles config for VS Code development containers

## Install

### Development Container

Visual Studio Code can be configured to clone and install this dotfiles config simply by updating your `settings.json` with the following two lines,

```json
{
  // ...
  "dotfiles.repository": "https://github.com/yumoose/container-dotfiles.git",
  "dotfiles.installCommand": "~/dotfiles/install.sh",
}
```

## Contents

### Bash-it

[Bash-it](https://github.com/Bash-it/bash-it) provides a mean as base set of functionality and is configured to,
* Make the terminal much less of an eye-sore 🎨
* Add Git aliases and supporting plugins 👨🏼‍💻
