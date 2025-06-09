# BYOD (Bring Your Own Distro): Curated Linux Customization Resources

Welcome to `fossmyanmar/BYOD`! This repository is a curated collection of resources for anyone interested in the "Bring Your Own Distro" philosophy – specifically focusing on customizing Linux Desktop Managers (DM), Window Managers (WM), and creating personalized Linux ISOs.

The aim is to gather useful links, tools, and guides to help you craft a Linux environment perfectly tailored to your needs.



---
[Slides](https://docs.google.com/presentation/d/1e6lfmVv73K0ROJLFIlxtkPAXmsJjr3e5imcnAasIZag/edit?usp=sharing)
---
[Discord](https://discord.gg/nbSFWXD6)
---

## Table of Contents

- [Custom Linux Desktop Managers & Window Managers](#custom-linux-desktop-managers--window-managers)
  - [Openbox](#openbox)
  - [Dotfiles Examples](#dotfiles-examples)
  - [Dotfile Management Tools](#dotfile-management-tools)
  - [Polybar (Status Bar)](#polybar-status-bar)
  - [Tint2 (Panel/Taskbar)](#tint2-paneltaskbar)
  - [Rofi (Application Launcher/Switcher)](#rofi-application-launcherswitcher)
  - [Eww (ElKowar's Wacky Widgets)](#eww-elkowars-wacky-widgets)
  - [Plymouth (Boot Splash Themes)](#plymouth-boot-splash-themes)
  - [Display Managers (Login Screens)](#display-managers-login-screens)
- [Linux ISO Customization](#linux-iso-customization)
  - [Cubic (Custom Ubuntu ISO Creator)](#cubic-custom-ubuntu-iso-creator)
  - [Debootstrap & Custom Builds from Scratch](#debootstrap--custom-builds-from-scratch)
  - [Ubuntu LiveCD/InstallCD Customization (Older Guides)](#ubuntu-livecdinstallcd-customization-older-guides)
  - [Ubuntu Autoinstall & Preseeding](#ubuntu-autoinstall--preseeding)

---

## Custom Linux Desktop Managers & Window Managers

Resources for customizing the look, feel, and functionality of your Linux desktop environment.

### Openbox

A highly configurable, stacking window manager.
*   **Setups & Base Configs:**
    *   [leomarcov/debian-openbox](https://github.com/leomarcov/debian-openbox/)
*   **Theme Collections:**
    *   [addy-dclxvi/openbox-theme-collections](https://github.com/addy-dclxvi/openbox-theme-collections)
    *   [zakuradev/openbox-themes](https://github.com/zakuradev/openbox-themes)
    *   [terroo/openbox-themes](https://github.com/terroo/openbox-themes/tree/main)

### Dotfiles Examples

Inspiration and examples for managing your personal configuration files.
*   [owl4ce/dotfiles](https://github.com/owl4ce/dotfiles)
*   [siduck/dotfiles (Openbox specific)](https://github.com/siduck/dotfiles/tree/openbox)
*   [Amitabha37377/Awful-DOTS (topbar_dock)](https://github.com/Amitabha37377/Awful-DOTS/tree/topbar_dock)
*   [Amitabha37377/Awful-DOTS (main)](https://github.com/Amitabha37377/Awful-DOTS)
*   [star.is-a.dev/projects/awm (Awesome WM based)](https://star.is-a.dev/projects/awm)
*   [elenapan/dotfiles](https://github.com/elenapan/dotfiles)
*   [AlphaTechnolog/dotfiles (Openbox specific)](https://github.com/AlphaTechnolog/dotfiles/tree/openbox)

### Dotfile Management Tools

Utilities to help you manage, version control, and deploy your dotfiles.
*   [Tech Intern - Dotfile Guide](https://tech-intern.github.io/dotfile/)
*   [Dotfiles.github.io - Utilities](https://dotfiles.github.io/utilities/)
*   [Chezmoi - Comparison Table](https://www.chezmoi.io/comparison-table/) (Compares various dotfile managers)
*   [Yadm - Yet Another Dotfiles Manager](https://yadm.io/)

### Polybar (Status Bar)

A fast and easy-to-use status bar.
*   **Themes:**
    *   [adi1090x/polybar-themes](https://github.com/adi1090x/polybar-themes)

### Tint2 (Panel/Taskbar)

A simple panel/taskbar developed for Openbox, but also works with other WMs.
*   **Themes:**
    *   [addy-dclxvi/tint2-theme-collections](https://github.com/addy-dclxvi/tint2-theme-collections)

### Rofi (Application Launcher/Switcher)

A window switcher, run dialog, ssh-launcher and dmenu replacement.
*   **Themes:**
    *   [newmanls/rofi-themes-collection](https://github.com/newmanls/rofi-themes-collection)
    *   [adi1090x/rofi](https://github.com/adi1090x/rofi)

### Eww (ElKowar's Wacky Widgets)

A standalone widget system made in Rust that allows you to create custom widgets.
*   **Core Project:**
    *   [elkowar/eww](https://github.com/elkowar/eww)
*   **Example Widgets/Themes:**
    *   [adi1090x/widgets](https://github.com/adi1090x/widgets) (Often used with Eww or Conky)

### Plymouth (Boot Splash Themes)

Graphical boot animation and logger.
*   **Themes:**
    *   [adi1090x/plymouth-themes](https://github.com/adi1090x/plymouth-themes)

### Display Managers (Login Screens)

*   **Web Greeter Concept:**
    *   [Web Greeter Page (Vercel App)](https://web-greeter-page.vercel.app/) (A concept for a web-based LightDM greeter)

---

## Linux ISO Customization

Tools and guides for creating your own customized Linux distribution ISO images.

### Cubic (Custom Ubuntu ISO Creator)

A GUI wizard to create a customized Live ISO image for Ubuntu and Debian-based distributions.
*   **Cubic Wiki - Start Page:** [PJ-Singh-001/Cubic/wiki/Start-Page](https://github.com/PJ-Singh-001/Cubic/wiki/Start-Page)
*   **Ask Ubuntu - Customizing with Cubic:** [How I can customize the Ubuntu live ISO installer using Cubic](https://askubuntu.com/questions/1289947/how-i-can-customize-the-ubuntu-live-iso-installer-using-cubic-add-remove-and)

### Debootstrap & Custom Builds from Scratch

Tools for creating a basic Debian/Ubuntu system from scratch, often used as a base for highly customized distros.
*   [mvallim/live-custom-ubuntu-from-scratch](https://github.com/mvallim/live-custom-ubuntu-from-scratch/)
*   [Anduin2017/AnduinOS](https://github.com/Anduin2017/AnduinOS) (Example of a custom OS build)

### Ubuntu LiveCD/InstallCD Customization (Older Guides)

These guides might be older but can still offer valuable insights.
*   **Ubuntu Community Help:**
    *   [LiveCDCustomization](https://help.ubuntu.com/community/LiveCDCustomization)
    *   [InstallCDCustomization](https://help.ubuntu.com/community/InstallCDCustomization)
*   **Blog Post (Portuguese):**
    *   [Criando seu LiveCD (hamacker.wordpress.com)](https://hamacker.wordpress.com/ubuntu-perfeito/crindo-seu-livecd/)

### Ubuntu Autoinstall & Preseeding

Automating Ubuntu installations using cloud-init (autoinstall) or preseed files.
*   **Generators & Examples:**
    *   [covertsh/ubuntu-autoinstall-generator](https://github.com/covertsh/ubuntu-autoinstall-generator)
    *   [covertsh/ubuntu-preseed-iso-generator](https://github.com/covertsh/ubuntu-preseed-iso-generator)
*   **Guides & Tutorials:**
    *   [Puget Systems: How To Make Ubuntu Autoinstall ISO with Cloud-init](https://www.pugetsystems.com/labs/hpc/How-To-Make-Ubuntu-Autoinstall-ISO-with-Cloud-init-2213/)
    *   [LinuxConfig.org: How to write and perform Ubuntu unattended installations with autoinstall](https://linuxconfig.org/how-to-write-and-perform-ubuntu-unattended-installations-with-autoinstall)
    *   [Imagineer.in: Packer Build for Ubuntu 20.04](https://imagineer.in/blog/packer-build-for-ubuntu-20-04/)
    *   [ManInTheIT.org: Ubuntu Autoinstall](https://manintheit.org/2021/03/18/ubuntu-autoinstall/)

---

##
Bookmarks file is available [BYOD.html](./BYOD.html)

You can now import this file into your browser:
```
  Chrome/Edge: Settings > Bookmarks > Import bookmarks and settings

  Firefox: Bookmarks > Manage Bookmarks > Import and Backup > Import Bookmarks from HTML
```

## Contributing

Found a broken link or have a suggestion for a new resource? Feel free to open an issue or submit a pull request! Your contributions are welcome to make this `fossmyanmar/BYOD` collection even better.

## License

This collection of bookmarks is provided as-is. Please refer to the individual licenses of the linked projects and resources.
