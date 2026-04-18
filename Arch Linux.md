# Software

- v2ray: `yay -S v2ray`
- v2rayN: `yay -S v2rayn-bin`
- Hiddify: `yay -S hiddify-app-bin`
- Clash Verge: `yay -S clash-verge-rev-bin`
- sublime: `yay -S sublime-text-4`
-  chrome/chromium: `yay -S google-chrome`/`yay -S chromium`
- gnome-console: `yay -S gnome-console`
- zsh:  
	- 安装： `yay -S zsh zsh-autosuggestions zsh-syntax-highlighting zsh-completions autojump`
	- 更改当前账户默认Shell： `chsh -s /usr/bin/zsh`
	- 更改root用户默认Shell： `sudo chsh -s /usr/bin/zsh root`
- on-my-zsh
	- 安装： `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`或者： `sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"`
	- 安装Powerlevel10k主题： 
		- `git clone --depth=1 https://gitee.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
		- 到`～/.zshrc`文件中设置主题：`ZSH_THEME="powerlevel10k/powerlevel10k"`
		- 重启终端
	- 使用`p10k configure`进行配置，字体如果使用配置不能下载，可以手动下载安装后继续配置。
	- 安装自动建议插件： 
		- `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
		- 添加到`～/.zshrc`文件：plugins后面的括号中以空分割，添加：`zsh-autosuggestions`
	- 安装语法高亮插件： 
		- `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git`
		- `echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc`
	- 重启终端
- vitrualbox: `yay -S virtualbox`
-  Mark Text: `yay -S marktext-appimg`
- Obsidian: `yay -S obsidian`
- Xournal++: `yay -S xournalpp`
- jdk: `yay -S jdk17-openjdk`
- jenv: 
	- 安装： `yay -S jenv`
	- 验证： `jenv doctor`
	- zsh配置： `echo 'eval "$(jenv init -)"' >> ~/.zshrc`
	- 启用export插件： 
		- `jenv enable-plugin export`
		- `exec $SHELL -l`
	- 添加jdk到jenv： `jenv add /usr/lib/jvm/java-17-openjdk`
	- 查看管理的jdk版本： `jenv versions`
	- 配置全局使用的jdk版本： `jenv global xxxx`
	- 配置本地目录的版本： `jenv local xxx`
	- 配置shell实例的版本： `jenv shell xxxx`
- maven: `yay -S maven`
	- 设置settings.xml文件
- MotrixNext: `yay -S motrix-next-bin`
- imFile: `yay -S imfile-bin`
- idea
- datagrip
- clion
- mysql: `yay -S mysql`
	- root/12345678
- Docker: `yay -S docker`
- go
- foxit-reader: `yay -S foxitreader`
- wps: `yay -S wps-office-cn`
- snipaste: `yay -S snipaste`
- copyq: `yay -S copyq`
- input-remapper: `yay -S input-remapper-bin`
-  wacom-utilty
- wacom-settings-git
- wechat: `yay -S wechat`
- QQ: `yay -S linuxqq-appimage`
- 腾讯会议: `yay -S tencent-meeting`
- telegram: `yay -S telegram-desktop`
- Tor Broswer: `yay -S tor-broswer-bin`
- VLC: 
	- `yay -S vlc`
	- `yay -S vlc-plugins-all`
- pCloud: `yay -S pcloud-drive`
- 百度云: `yay -S baidunetdisk-bin`
- Charles: `yay -S charles-bundled-java`
- Czkawka: `yay -S czkawka-gui-bin`
- Scrcpy: `yay -S scrcpy`
- Calibre: `yay -S calibre`
- Tweaks: `yay -S gnome-tweaks`
- fcitx5: 
	- `yay -S fcitx5-im`
	- `yay -S fcitx5-chinese-addons`
	- `yay -S fcitx5-qt`
	- `yay -S fcitx5-gtk`
	- 主题: 
		- `yay -S fcitx5-mellow-themes-git`
		- `yay -S fcitx5-themes-macos-git`
- fcitx5-rime: `yay -S fcitx5-rime`
	- 雾凇拼音: `yay -S rime-ice-git`
- Gestures: `yay -S gestures`
- TLP UI: `yay -S tlpui`
- Grub Customizer: `yay -S grub-customizer`
- Plymouth: `yay -S plymouth`
	- 主题: 
		- `yay -S plymouth-theme-arch-darwin plymouth-theme-arch-logo plymouth-theme-arch-logo-new plymouth-theme-arch-logo-gnomish plymouth-theme-arch-os`
		- `yay -S plymouth-theme-archlinux`
- Waydroid: 
	- `yay -S waydroid`
	- `yay -S waydroid-script-git`
	- `sudo waydroid-extras install libhoudini`

# Gnome-Shell Extensions

## User Extensions

通过`https://extensions.gnome.org/`进行安装。

- Add to Desktop
- AppIndicator and KStatusNotifierItem Support
- Astra Monitor
- Customize Clock on Lock Screen
- Dash to Dock
- Gnome 4x UI Improvements
- GSConnect
- Input Method Panel
- Logo Menu
- Lunar Calendar
- Removable Drive Menu
- Screenshot Window Sizer
- User Themes
- V-Shell
- Quick Settings Tweaks
- Copyous
- Open Bar
- Hide Top Bar

## System Extensions

通过命令行安装。

- CHC-E(Custom Hot Corners-Extended): `yay -S gnome-shell-extension-custom-hot-corners-extended`
- Unite: `yay -S gnome-shell-extension-unite`

# Configurations

- `~/.gitconfig`
- `~/.ssh/config`
- `~/.zshrc`
- `~/.local/share/fcitx5/rime/default.custom.yaml`
- `~/.local/share/fcitx5/rime/rime_ice.custom.yaml`