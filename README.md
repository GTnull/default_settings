# default_settings
-  安装cygwin，选择git curl wget zsh
- 安装oh-my-zsh
- 安装插件autosuggestions
    - Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```

    - Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

    ```sh
    plugins=(zsh-autosuggestions)
    ```

    - ```bindkey '^ ' autosuggest-accept``` 添加到plugins之后
- 安装插件zsh-syntax-highlighting
    - Clone this repository in oh-my-zsh's plugins directory:

       git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

    - Activate the plugin in `~/.zshrc`:

       plugins=( [plugins...] zsh-syntax-highlighting)

    - Source `~/.zshrc`  to take changes into account:

       source ~/.zshrc
- 将.gitconfig内容放到~目录下
