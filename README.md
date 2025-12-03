# My Custom GRUB Theme

A clean and modern GRUB bootloader theme featuring a sleek boxed menu UI, fully compatible with Linux and Windows systems.

---

## 📸 Preview

![GRUB Theme Preview](assets/background.png)

> Preview of the background image used in the GRUB boot menu.

---

## ⚙️ Installation

Follow these steps to install the theme:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Ashutoshbirje/my-grub-theme.git

2. **Navigate to the theme directory**
   ```bash
   cd my-grub-theme

3. **Create the GRUB themes directory (if it doesn’t exist)**
   ```bash

4. **Copy the theme to GRUB themes folder**
   ```bash

5. **Set the theme in GRUB configuration**
   Open the GRUB configuration file:

   ```bash
   sudo nano /etc/default/grub

   Add or modify this line:
   
   ```bash
   GRUB_THEME="/boot/grub/themes/your-theme-directory/theme.txt"


6. **Update GRUB**
   ```bash
   sudo update-grub

7. **Reboot to apply the theme**
   ```bash
   sudo reboot
