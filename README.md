these are my previously installed pacman packages and yes they all came from an endeavouros installation
```
curl -s https://raw.githubusercontent.com/user-nullxnull/my-previous-pacman-packages/refs/heads/main/installpackageswithnvidiaintel.txt | sudo pacman -S --needed - && systemctl enable gdm && dracut --add-confdir no-network /boot/initramfs-linux.img && dracut -f --add-confdir rescue /boot/initramfs-linux-fallback.img
```
