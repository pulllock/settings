# System Information

- OS Name: Arch Linux
- OS Type: 64 bit
- Desktop Environment: GNOME
- Windowing System: Wayland
# Software

## Software and Package management

- yay: `sudo pacman -S yay`
- CN keyring: `sudo pacman -S archlinuxcn-keyring`

## Software (Installed)

- Android Studio: Manual install to `/opt`
- Apostrophe (Markdown editor): `yay -S apostrophe`
- Audio Player (Decibels): `yay -S decibels`
- Aurynk (Mirror phone to computer): `yay -S aurynk`
- Baidu Net Disk: `yay -S baidunetdisk-bin`
- Calculator: `yay -S gnome-calculator`
- Calendar: `yay -S gnome-calendar`
- Camera (Snapshot): `yay -S snapshot`
- Clash Party: `yay -S mihomo-party-bin`
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
- Foliate（E-Book reader）: `yay -S foliate`
- Fonts: `yay -S gnome-font-viewer`
- Gnome Boxes: `yay -S gnome-boxes`（虚拟机）
- GNOME Color Manager: `yay -S gnome-color-manager`
- Google Chrome: `yay -S google-chrome`
- Gradia（给截图/图片添加注释）: `yay -S gradia tesseract-data-chi_sim tesseract-data-eng`
- Image Viewer (loupe): `yay -S loupe`
- JDK: `yay -S jdk25-openjdk`
- JetBrains IDEs: Manual install to `/opt`
	- CLion
	- DataGrip
	- Intellij IDEA
	- WebStorm
- Libreoffice: `yay -S libreoffice-fresh`
- Logs: `yay -S gnome-logs`
- Motrix Next: `yay -S motrix-next-bin`
- Music: `yay -S gnome-music`
- Obsidian: `yay -S obsidian-bin`
- Passwords and Keys: `yay -S seahorse`
- PeaZip: `yay -S peazip`
- Plymouth: `yay -S plymouth`
	- 主题: 
		- `yay -S plymouth-theme-arch-darwin plymouth-theme-arch-logo plymouth-theme-arch-logo-new plymouth-theme-arch-logo-gnomish plymouth-theme-arch-os`
		- `yay -S plymouth-theme-archlinux`
- Ptyxis: `yay -S ptyxis`
- QQ: `yay -S linuxqq`
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
- Visual Paradigm CE: Manual install to `~/Applications`
- Waydroid: 
	- `yay -S waydroid`
	- `yay -S waydroid-script-git`
	- `sudo waydroid-extras install libhoudini`
- Web (Epiphany): `yay -S epiphany`
- Wechat: `yay -S wechat-bin`
- Xournal++: `yay -S xournalpp`

## Software (Marked)

Flatpak: 

- Flatpak: `yay -S flatpak`
- Flathub Mirror: `sudo flatpak remote-modify flathub --url=https://mirrors.ustc.edu.cn/flathub`
- Flatseal

Common Software: 

- Bochs: 
	- `yay -S bochs`
	- `yay -S bochs-gdb-stub`
- Charles: `yay -S charles-bundled-java`
- Cutter: `yay -S rz-cutter`
- Czkawka: `yay -S czkawka-gui-bin`
- Gnome Console: `yay -S gnome-console`
- Grub Customizer: `yay -S grub-customizer`
- ImHex: `yay -S imhex`
- Input Remapper: `yay -S input-remapper-bin`
- Jenv:  `yay -S jenv`
- Maven: `yay -S maven`
- MySQL: `yay -S mysql`
- NASM: `yay -S nasm`
- pCloud: `yay -S pcloud-drive`
- Postman: `yay -S postman-bin`
- Sorftware: `yay -S gnome-software`
- Visual Studio Code: `yay -S visual-studio-code-bin`
- Wacom Utilty
- Wacom Settings

## ZSH

## ZSH

- Install: `yay -S zsh`
- Initial Zsh: 
	- Run command: `zsh`
	- Basic configuration options:
		- (1) History
			- History number in shell: `HISTSIZE=1000`
			- History file: `HISTFILE=~/.zsh_history`
			- History number in file: `SAVEHIST=1000`
		- (2) New completion system
			- (1)  Turn on completion with the default options.
		- (3) Keys
			- Emacs keymap
		- (4) Common shell options
			- Keep default configuration
- Make Zsh as default shell: `chsh -s /usr/bin/zsh`
- Plugins:
	- zsh-autosuggestions: `yay -S zsh-autosuggestions`
	- zsh-syntax-highlighting: `yay -S zsh-syntax-highlighting`
	- zsh-completions: `yay -S zsh-completions`
	- zoxide: `yay -S zoxide`

## Nerd Font

- JetBrains Mono Nerd Font: `yay -S ttf-jetbrains-mono-nerd`

## Starship

- Install: `yay -S starship`
- Enable Starship: add `eval "$(starship init zsh)"` to `.zshrc` file.
- Configuration, file: `~/.config/starship.toml`

# Fonts

- Microsoft Windows 11 TrueType fonts:
	- Manual download ISO file to `~/.cacahe/yay/ttf-ms-win11/`
	- Copy `install.wim` file from the ISO: `souce/install.wim` to `~/.cache/yay/ttf-ms-win11`
	- Install `wimlib` package: `yay -S wimlib` 
	- `wimextract ~/.cache/yay/ttf-ms-win11/install.wim 1 /Windows/{Fonts/"*".{ttf,ttc},System32/Licenses/neutral/"*"/"*"/license.rtf} --dest-dir ~/.cache/yay/ttf-ms-win11/`
	- `yay -S --mflags "--skipchecksums" ttf-ms-win11`
	- Copy the `.ttc` font files to `/usr/share/fonts/TTF`
	- `sudo fc-cache -fv`
- Noto Fonts: `yay -S noto-fonts noto-fonts-cjk noto-fonts-emoji`
- Source Han Sans / Serif: `yay -S adobe-source-han-sans-cn-fonts adobe-source-han-serif-cn-fonts`

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
- ~~Unite~~: `yay -S gnome-shell-extension-unite`

# Configurations

- `~/.gitconfig`
- `~/.ssh/config`
- `~/.zshrc`
- `~/.config/starship.toml`
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

# Settings

## System Settings

## Tweaks

- Fonts:
	- Preferred Fonts: 
		- Interface Text: Adwaita Sans
		- Document Text: Adwaita Sans
		- Monospace Text: Adwaita Mono
	- Redering:
		- Hinting: Slight
		- Antialiasing: Subpixel (for LCD screens)
	- Size: 
		- Scaling Factor: 1.20