## ⚠ Warning
```log
Most of these scripts have been discontinued.
Do not use them. Please wait until BashDocs 2.0 releases.
Proceed with caution! 
```

## 🐦 Useful Scripts
<!--[Github](https://github.com/Dogzocute-D-e-v/Dogzocute-Core) -->

| Pterodactyl Scripts | Available |
|:------------:|:-------------:|
| [**Install**](https://github.com/Dogzocute-D-e-v/useful-scripts/blob/main/scripts/install.sh)  | ❌  |
| [**Update**](https://github.com/Dogzocute-D-e-v/useful-scripts/blob/main/scripts/update.sh)  | ❌  |
| [**Uninstall**](https://github.com/Dogzocute-D-e-v/useful-scripts/blob/main/scripts/remove.sh)  | ❌  |
| [**PhpMyAdmin**](https://github.com/Dogzocute-D-e-v/useful-scripts/blob/main/scripts/phpmyadmin-themes.sh)  | ✅ |

# Picking a Server OS
Pterodactyl runs on a wide range of operating systems, so pick whichever you are most comfortable using.

| Operating System | Version | Supported | Notes |
|:----------:|:-------------:|:-------------:|----------|
| **Ubuntu**   |  20.04  |✅| Documentation written assuming Ubuntu 20.04 as the base OS.    |
|| 22.04    |✅| MariaDB can be installed without the repo setup script.    |
| **CentOS**    | 7    |❌| 	Extra repos are required.    |
|| 8    |❌| Note that CentOS 8 is EOL. Use Rocky or Alma Linux.    |
| **Debian**    | 11    |❌| Row 5    |
|| 12    |❌| Row 6    |

## Install Script

Usage:
Download and execute the script. Answer the questions asked by the script and it will take care of the rest.
```bash
cd /root && wget https://src.dogzocute.space/scripts/install.sh && bash install.sh
```
Warning: if the script dosen't work please do
```bash
sudo apt-get install dos2unix
cd /root
wget https://src.dogzocute.space/scripts/install.sh
dos2unix install.sh
bash install.sh
```

what's inside of [install.sh](https://github.com/Dogzocute-D-e-v/useful-scripts/blob/main/scripts/install.sh)

please follow the instructions here to continue the installation after running the script

[instructions](https://github.com/Dogzocute-D-e-v/useful-scripts/blob/main/tutorials/install.md)

## Update Script
Usage:
Download and execute the script. Answer the questions asked by the script and it will take care of the rest.

```bash
cd /var/www/pterodactyl && wget https://src.dogzocute.space/scripts/update.sh && bash update.sh
```

what's inside of [update.sh](https://github.com/Dogzocute-D-e-v/useful-scripts/blob/main/scripts/update.sh)

## Remove Script
Usage:
Download and execute the script. Answer the questions asked by the script and it will take care of the rest.

```bash
cd /var/www/pterodactyl && wget https://src.dogzocute.space/scripts/remove.sh && bash remove.sh
```

what's inside of [remove.sh](https://github.com/Dogzocute-D-e-v/useful-scripts/blob/main/scripts/remove.sh)


## PhpMyadmin Theme Installer
Usage:
Download and execute the script. Answer the questions asked by the script and it will take care of the rest.

```bash
cd /var/www/phpmyadmin/themes && wget https://src.dogzocute.space/scripts/phpmyadmin-themes.sh && bash phpmyadmin-themes.sh
```

what's inside of [phpmyadmin-themes.sh](https://github.com/Dogzocute-D-e-v/useful-scripts/blob/main/scripts/phpmyadmin-themes.sh)

## ⚠ Warning
```log
Most of these scripts have been discontinued.
Do not use them. Please wait until BashDocs 2.0 releases.
Proceed with caution! 
```
