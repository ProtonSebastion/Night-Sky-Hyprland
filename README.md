# Showcase
<img width="1920" height="1079" alt="Preview" src="https://github.com/user-attachments/assets/2c3ad09d-dc49-4389-86cb-0257f3256728" />


# ProtonSebastian Config
Technically This is A small project And Im still new to the Hyprland Community

And There are still a Few Things That Needs to Be Future Proofed

# ⚠️ Warning (For Nvidia Users)
Reminder before you Download This Rice Id Recommend Checking Your grub config and Your mkincitipo Config To The following:

Go to /etc/default/grub And change the GRUB_CMDLINE_LINUX_DEFAULT="loglevel=3 quiet To GRUB_CMDLINE_LINUX_DEFAULT="loglevel=3 quiet nvidia-drm.modeset=1"

Dont forget to sudo grub-mkconfig -o /boot/grub/grub.cfg After Applying those changes

For mkinitcpio Go to /etc/mkinitcpio.conf And Change the Line MODULES=() To MODULES=(nvidia nvidia_modeset nvidia_uvm nvidia_drm)

After Applying mkinitcpio.conf Dont Forget To sudo mkinitcpio -P

# Features
1.This Hyprrice Supports Nvidia Gpus

2.This Hyprrice Uses Kitty As The Terminal

3.This Hyprice Will be changing to Quickshell (Soon)
# Credits
[Jakoolit](https://github.com/jakoolit)

[end-4](https://github.com/end-4)

[YourLocalException](https://github.com/yourlocalexception) This Guy Is a Monkey


