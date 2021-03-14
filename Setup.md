https://nickjanetakis.com/blog/the-tools-i-use

https://www.youtube.com/playlist?list=PL-v3vdeWVEsXo87wHeVSP_x1KTX4G1l8Y

https://github.com/junegunn/fzf

https://github.com/nickjj/dotfiles

Install tmux 3.x :

sudo apt update && sudo apt install -y git automake build-essential pkg-config libevent-dev libncurses5-dev byacc bison \
rm -fr /tmp/tmux \
git clone https://github.com/tmux/tmux.git /tmp/tmux \
cd /tmp/tmux \
git checkout 3.0 \
sh autogen.sh \
./configure && make \
sudo make install \
cd - \
rm -fr /tmp/tmux \

try using tmux then do ctrl +b then press d.

https://nickjanetakis.com/blog/creating-and-managing-a-gpg-key-pair

https://skeptric.com/wsl2-xserver/#:~:text=Press%20the%20Windows%20Start%20Button,%22Add%20Rule...%22

https://stackoverflow.com/questions/61110603/how-to-set-up-working-x11-forwarding-on-wsl2


<br>
vim save and quit: shift +ZZ <br>
vim quit without saving: shift +ZQ
<br>

For github credentials:
https://nickjanetakis.com/blog/signing-and-verifying-git-commits-on-the-command-line-and-github <br>
