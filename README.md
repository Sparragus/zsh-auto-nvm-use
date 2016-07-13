# zsh-auto-use-nvm

`zsh-auto-use-nvm` is a zsh plugin that automatically loads the node version specified in `.nvmrc`.

The code is completely taken from the [nvm's GitHub repository](https://github.com/creationix/nvm#zsh).

## Installation

### Using [Antigen](https://github.com/zsh-users/antigen)
Bundle `zsh-auto-use-nvm` in your `.zshrc`
```
antigen bundle Sparragus/zsh-auto-use-nvm
```

### As an [Oh My ZSH!](https://github.com/robbyrussell/oh-my-zsh) custom plugin
Clone `zsh-auto-use-nvm` into your custom plugins repo.

```
git clone https://github.com/Sparragus/zsh-auto-use-nvm ~/.oh-my-zsh/custom/plugins/zsh-auto-use-nvm
```

Then load as a plugin in your `.zshrc`

```
plugins+=(zsh-auto-use-nvm)
```
