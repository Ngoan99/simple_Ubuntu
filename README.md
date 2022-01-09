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
