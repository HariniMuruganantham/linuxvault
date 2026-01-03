# Logical Volume Management (LVM)

LVM allows flexible disk management by combining multiple physical disks.

---

## LVM Components

| Component | Description |
|---------|-------------|
| PV | Physical Volume |
| VG | Volume Group |
| LV | Logical Volume |

---

## Creating Physical Volume

$ sudo pvcreate /dev/sdb

---

## Creating Volume Group

$ sudo vgcreate vgdata /dev/sdb

---

## Creating Logical Volume

$ sudo lvcreate -n lvdata -L 5G vgdata

---

## Formatting and Mounting

$ sudo mkfs.ext4 /dev/vgdata/lvdata  
$ sudo mount /dev/vgdata/lvdata /mnt/data
