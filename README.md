# zsh-auto-nvm-use

`zsh-auto-nvm-use` is a zsh plugin that automatically loads the node version specified in `.nvmrc`.

The code is completely taken from the [nvm's GitHub repository](https://github.com/creationix/nvm#zsh).

## Installation

### Using [Antigen](https://github.com/zsh-users/antigen)
Bundle `zsh-auto-nvm-use` in your `.zshrc`
```
antigen bundle Sparragus/zsh-auto-nvm-use
```

### As an [Oh My ZSH!](https://github.com/robbyrussell/oh-my-zsh) custom plugin
Clone `zsh-auto-nvm-use` into your custom plugins repo.

```
git clone https://github.com/Sparragus/zsh-auto-nvm-use ~/.oh-my-zsh/custom/plugins/zsh-auto-nvm-use
```

Then load as a plugin in your `.zshrc`

```
plugins+=(zsh-auto-nvm-use)
```
