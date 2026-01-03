# Package Management 

---

## Purpose

Package management is used to install, update, remove, and manage software on a Linux
system.

Different Linux distributions use different package managers.

---

## Key Concepts

- Packages are precompiled software files
- Repositories store packages online
- Package managers download and install packages automatically
- Dependencies are resolved automatically

---

## Popular Package Managers

| Distribution | Package Manager |
|--------------|-----------------|
| Ubuntu / Debian | apt |
| Fedora / CentOS / Rocky | dnf |
| Arch Linux | pacman |

---

## Common Commands – apt

Update package list:

```

sudo apt update

```

Upgrade packages:

```

sudo apt upgrade

```

Install package:

```

sudo apt install nginx

```

Remove package:

```

sudo apt remove nginx

```

---

## Common Commands – dnf

Install package:

```

sudo dnf install nginx

```

Remove package:

```

sudo dnf remove nginx

```

---

## Common Commands – pacman

Install package:

```

sudo pacman -S nginx

```

Remove package:

```

sudo pacman -R nginx

```

---

## Summary

- Package managers simplify software installation  
- Automatically manage dependencies  
- Different distributions use different tools
```
