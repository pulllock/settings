# Software

Software and Package management:

- yay: `sudo pacman -S yay`
- CN keyring: `sudo pacman -S archlinuxcn-keyring`

Software:

- Android Studio: Manual install to `/opt`
- Apostrophe (Markdown editor): `yay -S apostrophe`
- Audio Player (Decibels): `yay -S decibels`
- Aurynk (Mirror phone to computer): `yay -S aurynk`
- Baidu Net Disk: `yay -S baidunetdisk-bin`
- Calculator: `yay -S gnome-calculator`
- Calendar: `yay -S gnome-calendar`
- Camera (Snapshot): `yay -S snapshot`
- Clash Verge: `yay -S clash-verge-rev-bin`
- Console: `yay -S gnome-console``
- dconf Editor: `yay -S dconf-editor`
- Disks: `yay -S gnome-disk-utility`
- Disk Usage Analyzer (Baobab): `yay -S baobab`
- Docker: `yay -S docker`
- Document Viewer (Papers): `yay -S papers`
- Extension Manager: `yay -S extension-manager`
- Extensions
- Fcitx 5: 
	- `yay -S fcitx5-im`
	- 主题: 
		- `yay -S fcitx5-mellow-themes-git`
	- fcitx5-rime: `yay -S fcitx5-rime`
		- 万象拼音基础版: 
			- `yay -S rime-wanxiang-pinyin`
- File Roller: `yay -S file-roller`
- Files
- Firefox: `yay -S firefox-nightly-bin`, `yay -S firefox-developer-edition`
- Foliate（EPUB阅读器）: `yay -S foliate`
- Fonts: `yay -S gnome-font-viewer`
- Gnome Boxes: `yay -S gnome-boxes`（虚拟机）
- GNOME Color Manager: `yay -S gnome-color-manager`
- Gnome Console: `yay -S gnome-console`
- Google Chrome: `yay -S google-chrome`
- Gradia（给截图/图片添加注释）: `yay -S gradia`
- Image Viewer (loupe): `yay -S loupe`
- JDK: `yay -S jdk25-openjdk`
- JetBrains IDEs: 手动安装到 `/opt`
	- CLion
	- DataGrip
	- Intellij IDEA
	- WebStorm
- Logs: `yay -S gnome-logs`
- Motrix Next: `yay -S motrix-next-bin`
- Music: `yay -S gnome-music`
- Noto Fonts: `yay -S noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra`
- Obsidian: `yay -S obsidian-bin`
- Passwords and Keys: `yay -S seahorse`
- PeaZip: `yay -S peazip`
- Plymouth: `yay -S plymouth`
	- 主题: 
		- `yay -S plymouth-theme-arch-darwin plymouth-theme-arch-logo plymouth-theme-arch-logo-new plymouth-theme-arch-logo-gnomish plymouth-theme-arch-os`
		- `yay -S plymouth-theme-archlinux`
- QQ: `yay -S linuxqq-appimage`
- Video Player (Showtime)
- Settings
- Sublime Text: `yay -S sublime-text-4`
- System Monitor
- Telegram: `yay -S telegram-desktop`
- Terminator: `yay -S terminator`
- Text Editor: `yay -S gnome-text-editor`
- TLP UI: `yay -S tlpui`
- Tweaks: `yay -S gnome-tweaks`
- Video Player (Showtime): `yay -S showtime`
- Vim: `yay -S vim`
- Visual Paradigm CE: `yay -S visual-paradigm-community`
- Waydroid: 
	- `yay -S waydroid`
	- `yay -S waydroid-script-git`
	- `sudo waydroid-extras install libhoudini`
- Web (Epiphany): `yay -S epiphany`
- Wechat: `yay -S wechat-appimage`
- WPS 365: `yay -S wps-office-365`, `yay -S wps-office-365-fonts`
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

通过 Extension Manager或 `https://extensions.gnome.org/`进行安装。

- AppIndicator and KStatusNotifierItem Support
- Astra Monitor
- Blur my Shell
- Copyous
- Customize Clock on Lock Screen
- Dash to Dock
- Extension List
- Gnome 4x UI Improvements
- GSConnect
- Hide Top Bar
- Just Perfection
- Lunar Calendar
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

# Firefox extensions

- Authenticator
- Dark Reader
- Gnome Shell integration
- Motrix Next Extension
- Proxy SwitchyOmega 3
- Tabliss
- Tampermonkey

# Chrome extensions

- Authenticator
- Caretab
- Dark Reader
- FireShot
- Gnome Shell integration
- Motrix Next Extension
- Proxy SwitchyOmega 3
- Tampermonkey