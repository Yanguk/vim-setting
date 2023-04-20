# vim-setting

i# install system-wide (or ~/.local/share/fonts for user-wide)
sudo mkdir -p /usr/share/fonts/truetype/nanum-gothic
sudo mv *.ttf /usr/share/fonts/truetype/nanum-gothic

## mac font folder
~/Library/Fonts

## font 설치
unzip ./TrueType.zip  && mv ./TrueType/*.ttf ~/Library/Fonts && rm -r ./TrueTpye

## 터미널 설정 경로
ln ./.zshrc ~/.zshrc

## nvim 설정 경로
mkdir ~/.config/nvim
ln ./nvim/init.vim ~/.config/nvim/init.vim


## 번들 설치
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

