------------------------------SIMPLE_UBUNTU----------------------------

#install gnome tweak, gnome shell extention
- https://linuxhint.com/gnome_tweak_installation_ubuntu/
- https://linuxconfig.org/how-to-install-gnome-shell-extensions-on-ubuntu-18-04-bionic-beaver-linux
- https://extensions.gnome.org/
  + Gradient Top Bar 
  + Hide Activities Button 
  + Hide Top Bar
  
#disable dock

    gnome-extensions disable ubuntu-dock@ubuntu.com
    
#set xfce4-terminal to default terminal
 
    sudo apt install xfce4-terminal
    sudo update-alternatives --config x-terminal-emulator
    
  - select number related to xfce4
  
#install zsh shell and ohmyzsh
- https://www.unixmen.com/install-oh-zsh-ubuntu-arch-linux-fedora/

+ change theme: find and edit line ZSH_THEME="YOUR_THEME" in .zshrc file, with YOUR_THEME refer here https://github.com/ohmyzsh/ohmyzsh/wiki/themes

      ZSH_THEME="YOUR_THEME"
      
- install plugin autosuggestion, syntax highlighting, fzf:

        git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions

        git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
        
        git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
        ~/.fzf/install
  
- add plugin: find and edit again for the same bellow in .zshrc file
  
        plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
