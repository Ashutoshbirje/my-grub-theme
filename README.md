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

2. **Create the GRUB themes directory (if it doesn’t exist)**
   ```bash
   sudo mkdir -p /boot/grub/themes

3. **Copy the theme to GRUB themes folder**
   ```bash
   sudo cp -r my-grub-theme/* /boot/grub/themes/mytheme/

4. **Open the GRUB configuration file**

   ```bash
   sudo nano /etc/default/grub

5. **Add or modify this line**

   ```bash
   GRUB_THEME=/boot/grub/themes/mytheme/theme.txt

6. **Update GRUB**
   ```bash
   sudo update-grub

7. **Reboot to apply the theme**
   ```bash
   sudo reboot

---

## 📁 Folder Structure
```
my-grub-theme/
├── assets/
│   ├── background.png         # Background image
│   ├── terminal_box_/*.png    # Terminal box image
│   └── terminus-/*.pf2        # Custom font
├── icons/
│   └── img.png                # Custom image
├── theme.txt                  # GRUB theme configuration
└── README.md                  # This file
```

---

## ✏️ Customization 

You can customize:

- **Background image** → assets/background.png

- **Terminal box** → assets/terminal_box_/*.png

- **Font** → assets/terminus-/*.pf2

- **Menu position & colors** → theme.txt

---

## 👨‍💻 Author

Created by Ashutosh Birje
