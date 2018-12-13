# default_settings
-  安装cygwin，选择git curl wget zsh
- 安装oh-my-zsh
- 安装插件autosugges
    - Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```

    - Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

    ```sh
    plugins=(zsh-autosuggestions)
    ```

    - ```bindkey '^ ' autosuggest-accept``` 添加到plugins之后
- 将.gitconfig内容放到~目录下
