# SYSTEMD – Service Management in Linux

---

## Purpose

SYSTEMD is the modern initialization system used in Linux to manage system services,
startup sequence, background processes, and logging.

It replaces the older SysV init system.

---

## Key Concepts

- Manages services using **unit files**
- Controls system startup using **targets**
- Provides centralized logging with **journal**
- Main management tools:
  - `systemctl`
  - `journalctl`

---

## Boot Process Flow

```

Power ON → BIOS/UEFI → Boot Loader → Kernel → systemd → Target → Login

```

---

## Unit File Locations

| Path | Purpose |
|------|--------|
| /lib/systemd/system | Default unit files |
| /etc/systemd/system | Custom service files |

---

## Common Commands

Check service status:

```

systemctl status sshd

```

Start service:

```

systemctl start sshd

```

Stop service:

```

systemctl stop sshd

```

Restart service:

```

systemctl restart sshd

```

Enable service at boot:

```

systemctl enable sshd

```

Disable service at boot:

```

systemctl disable sshd

```

---

## Working with Targets

View default target:

```

systemctl get-default

```

Change default target:

```

systemctl set-default graphical.target

```

---

## Viewing Logs

Show logs for service:

```

journalctl -u sshd.service

```

---

## Reload Configuration

```

systemctl daemon-reload

```

---

## Summary

- SYSTEMD controls services and system startup  
- Uses `systemctl` for management  
- Uses `journalctl` for logs  
- Replaces traditional init systems
```
