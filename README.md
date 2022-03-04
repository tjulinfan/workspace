## Configurations of workspace

* Install zsh and oh-my-zsh [Guide](https://github.com/ohmyzsh/ohmyzsh)
* Enable [macos plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/macos)
* Install zsh-autosuggestions plugin
  
Install custom plugin
```shell
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
Enable it in ~/.zshrc
```shell
plugins=(
  ...
  zsh-autosuggestions
)
```
