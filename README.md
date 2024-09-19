# install

```bash
mkdir -p ~/build
cd ~/build
git clone https://github.com/christitustech/mybash
```

```bash
cd ~/build/mybash
./setup.sh
```

install jetbrainsmono nerdfont:

```bash
wget -P ~/.local/share/fonts https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/JetBrainsMono.zip \
&& cd ~/.local/share/fonts \
&& unzip JetBrainsMono.zip \
&& rm JetBrainsMono.zip \
&& fc-cache -fv
```
