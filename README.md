# Linux Mint - Debian Distribution configuration

LMDE 4 Debbie - https://www.linuxmint.com/download_lmde.php

TO-DO:
- Assign bar to the right
- Download Howdy Debian

```
sudo apt install remmina -y
```

Howdy - https://github.com/boltgolt/howdy
```
sudo howdy add
```

Lotion - https://github.com/puneetsl/lotion

Sublime Text
```
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
sudo apt-get update
sudo apt-get install sublime-text
```
