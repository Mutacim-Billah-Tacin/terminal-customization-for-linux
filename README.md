$ sudo apt install zsh

> exit > 1 > 2 > 1 > 0

<<<< Set zsh as default >>>>

$ chsh -s $(which zsh)

$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

> y

$ git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions

$ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting

<<<< edit .zshrc to include plugins >>>>

$ nano .zshrc

plugins=(git zsh-autosuggestions zsh-syntax-highlighting history)

<<<< download and set any nerdfonts >>>>

https://www.nerdfonts.com/

<<<< move the font file >>>>

$ sudo mv __font__ /usr/share/fonts/

$ sudo fc-cache -fv

$ git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

<<<< edit .zshrc >>>>

$ nano .zshrc

ZSH_THEME="powerlevel10k/powerlevel10k"

> exit > y > y > y > 1 > n > your_choice
> y > y > finish
