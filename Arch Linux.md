# Software

- Apostrophe: `yay -S apostrophe`（markdown编辑器）
- 百度云: `yay -S baidunetdisk-bin`
- Bochs: 
	- `yay -S bochs`
	- `yay -S bochs-gdb-stub`
- Charles: `yay -S charles-bundled-java`
- Chrome/Chromium: `yay -S google-chrome`/`yay -S chromium`
- Clash Verge: `yay -S clash-verge-rev-bin`
- Cutter: `yay -S rz-cutter`
- Czkawka: `yay -S czkawka-gui-bin`
- dconf Editor: `yay -S dconf-editor`
- Docker: `yay -S docker`
- Fcitx5: 
	- `yay -S fcitx5-im`
	- `yay -S fcitx5-configtool`
	- `yay -S fcitx5-gtk`
	- 主题: 
		- `yay -S fcitx5-mellow-themes-git`
		- `yay -S fcitx5-themes-macos-git`
	- fcitx5-rime: `yay -S fcitx5-rime`
		- 雾凇拼音: `yay -S rime-ice-git`
		- 万象拼音基础版: 
			- `yay -S rime-wanxiang-pinyin`
			- `yay -S rime-wanxiang-sogou`
- Foliate: `yay -S foliate`（EPUB阅读器）
- Gnome Boxes: `yay -S gnome-boxes`（虚拟机）
- Gnome Console: `yay -S gnome-console`
- Go
- Gradia: `yay -S gradia`（给截图/图片添加注释）
	- `yay -S tesseract-data-chi_sim`
- Grub Customizer: `yay -S grub-customizer`
- Hiddify: `yay -S hiddify-app-bin`
- ImHex: `yay -S imhex`
- Input Remapper: `yay -S input-remapper-bin`
- Jdk: `yay -S jdk17-openjdk`
- Jenv: 
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
- JetBrains IDEs: 
	- CLion
	- DataGrip
	- Intellij IDEA
	- WebStorm
- Maven: `yay -S maven`
	- 设置settings.xml文件
- MotrixNext: `yay -S motrix-next-bin`
- 视频播放器：MPV
	- `yay -S celluloid`
- MySQL: `yay -S mysql`
	- root/12345678
- NASM: `yay -S nasm`
- Obsidian: `yay -S obsidian-bin`
- pCloud: `yay -S pcloud-drive`
- Plymouth: `yay -S plymouth`
	- 主题: 
		- `yay -S plymouth-theme-arch-darwin plymouth-theme-arch-logo plymouth-theme-arch-logo-new plymouth-theme-arch-logo-gnomish plymouth-theme-arch-os`
		- `yay -S plymouth-theme-archlinux`
- Postman: `yay -S postman-bin`
- QQ: `yay -S linuxqq-appimage`
- Scrcpy: `yay -S scrcpy`
- Sublime Text: `yay -S sublime-text-4`
- Telegram: `yay -S telegram-desktop`
- TLP UI: `yay -S tlpui`
- Tor Broswer: `yay -S tor-broswer-bin`
- Tweaks: `yay -S gnome-tweaks`
- V2ray: `yay -S v2ray`
- V2rayN: `yay -S v2rayn-bin`
- Visual Paradigm CE: `yay -S visual-paradigm-community`
- Visual Studio Code: `yay -S visual-studio-code-bin`
- Wacom Utilty
- Wacom Settings
- Waydroid: 
	- `yay -S waydroid`
	- `yay -S waydroid-script-git`
	- `sudo waydroid-extras install libhoudini`
- Wechat: `yay -S wechat-appimage`
- Wps: `yay -S wps-office-cn`
- Xournal++: `yay -S xournalpp`
- Zsh:  
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

# Gnome-Shell Extensions

## User Extensions

通过`https://extensions.gnome.org/`进行安装。

- Add to Desktop
- AppIndicator and KStatusNotifierItem Support
- Astra Monitor
- Blur my Shell
- Copyous
- Customize Clock on Lock Screen
- Dash to Dock
- Gnome 4x UI Improvements
- GSConnect
- Hide Top Bar
- Input Method Panel
- Just Perfection
- Logo Menu
- Lunar Calendar
- Open Bar
- Quick Settings Tweaks
- Removable Drive Menu
- Screenshot Window Sizer
- User Themes
- V-Shell

## System Extensions

通过命令行安装。

- CHC-E(Custom Hot Corners-Extended): `yay -S gnome-shell-extension-custom-hot-corners-extended`
- Unite: `yay -S gnome-shell-extension-unite`

# Configurations

- `~/.gitconfig`
- `~/.ssh/config`
- `~/.zshrc`
- Rime custom configuration: `~/.local/share/fcitx5/rime/default.custom.yaml`
- Rime Ice custom configuration: `~/.local/share/fcitx5/rime/rime_ice.custom.yaml`
- Rime Wanxiang custom configuration: `~/.local/share/fcitx5/rime/wanxiang.custom.yaml`
- `~/.config/fontconfig/fonts.conf`

# Custom Shortcuts

- Toggle Extension: Hide Top Bar
	- Name: Toggle Extension: Hide Top Bar
	- Command: `bash -c 'UUID="hidetopbar@mathieu.bidon.ca"; STATE=$(gnome-extensions info "$UUID" | grep "State" | awk "{print \$2}"); if [ "$STATE" == "ACTIVE" ]; then gnome-extensions disable "$UUID"; else gnome-extensions enable "$UUID"; fi'`
	- Shortcut: `Super + \``

# Boot

## EFI

- `Arch/`：Arch Linux启动路径
	- `grubx64.efi`：Grub引导
- `Boot/`：兜底启动路径
	- `BootX64.efi`：UEFI规范定义的默认启动文件，和`Arch/grubx64.efi`是同一个文件
- `Microsoft/`
	- `Boot/`：Windows启动路径
		- `bootmgrfw.efi`：Windows启动入口
		- `BCD`：启动配置数据库

## Boot

- `efi/`：
	- `EFI/`：EFI目录
- `grub/`：GRUB目录
	- `grub.cfg`：启动菜单配置
	- `grubenv`
	- `unicode.pf2`
	- `fonts/`：字体
	- `themes/`：主题
	- `locale/`
	- `x86_64-efi/`：GRUB模块
- `initramfs-linux.img`：在内核真正挂载根文件系统之前加载驱动（磁盘、文件系统、NVMe、RAID），挂载root，切换到真实系统。
- `initramfs-linux-fallback.img`：不依赖autodetect，包含更多驱动。
- `intel-ucode.img`：CPU微码
- `vmlinuz-linux`：linux内核

## BIOS

- BIOS启动项顺序：
	- UEFI（兜底启动）
	- Windows Boot Manager
	- Arch
- 启动Windows配置：
	- Boot Configuration：Secure Boot设置为ON
	- Storage：SATA/NVMe Operation设置为RAID On
- 启动Arch Linux配置：
	- Boot Configuration：Secure Boot设置为OFF
	- Storage：SATA/NVMe Operation设置为AHCI/NVMe