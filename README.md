these are my previously installed pacman packages and yes they all came from an endeavouros installation
```
curl -s https://raw.githubusercontent.com/user-nullxnull/my-previous-pacman-packages/refs/heads/main/installpackageswithnvidiaintel.txt | sudo pacman -S --needed - && sudo systemctl enable gdm && sudo dracut --force && sudo dracut -f --add-confdir rescue /boot/initramfs-linux-fallback.img
```
