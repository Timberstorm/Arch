# Arch Linux file repository for builds

sudo pacman -S git
mkdir .git
cd .git
git clone https://github.com/Timberstorm/Arch.git
cd Arch
sudo -s
pacman -S --needed - < (Name of file from list)
