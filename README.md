# Grub Dark Theme

A 1080p dark grub theme made for personal use made after combining [Poly Dark](https://github.com/shvchk/poly-dark) and [Yorha](https://github.com/OliveThePuffin/yorha-grub-theme) themes.

# Installation

Clone the repository:
```
git clone --depth 1 https://github.com/shashotoNur/grub-dark-theme
```

Copy the theme to grub's directory:
```
sudo cp -r grub-dark-theme/theme /boot/grub/themes/
```

Edit the grub config file: `/etc/default/grub` and modify the `GRUB_THEME` line to:
```
GRUB_THEME="/boot/grub/themes/theme/theme.txt"
```

Update grub configuration:
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
