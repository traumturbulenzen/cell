# cell
Plymouth Theme for Ubuntu 20.04 LTS

## Install instructions in **five steps**

1. _move_ or copy folder to **`/usr/share/plymouth/themes/`**
2. run **`sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/cell/cell.plymouth 110`**
3. run **`sudo update-alternatives --config default.plymouth`**
4. select the theme
5. run **`sudo update-initramfs -c -k $(uname -r)`**
