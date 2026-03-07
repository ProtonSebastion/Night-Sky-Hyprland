# Preview
<img width="1920" height="1079" alt="Preview" src="https://github.com/user-attachments/assets/5c3b17a1-b5c6-4d24-8206-37ec00057fa8" />

# Night Sky Hyprland

Made By ProtonSebastian

This HyprRice Has Some Rooms To improve

# Features

1.Supports Nvidia gpus

2.Uses Kitty Terminal

3.Will Change to quickshell(Soon)

# ⚠️ Warning (For Nvidia Users)

Before Donloawding The rice Pls Add These For Grub,mkinitcpio and Environment

For /etc/mkinitcpio.conf  change the MODULES=() With MODULES=(nvidia nvidia_modeset nvidia_uvm nvidia_drm)

For /etc/default/grub Add nvidia-drm.modeset=1 Inside The GRUB_CMDLINE_LINUX_DEFAULT (GRUB_CMDLINE_LINUX_DEFAULT="loglevel=3 quiet nvidia-drm.modeset=1")

For /etc/environment Add NVD_BACKEND=direct


