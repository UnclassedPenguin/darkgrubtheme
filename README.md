## To install 
- Copy the folder darkminimal to /boot/grub/themes/ 
- Change the theme line in /etc/default/grub to:
    GRUB_THEME="/boot/grub/themes/darkminimal/theme.txt"
- Then either:
```shell
    sudo update-grub
```
    or
```shell
    sudo grub-mkconfig -o /boot/grub/grub.cfg
```
