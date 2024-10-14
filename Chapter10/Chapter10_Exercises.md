# Chapter 10: Exercises

## Exercise 1: Exploring Filesystem Types

- **Objective**: Understand different filesystem types and their features.
- **Tasks**:
  1. List all available filesystems on your system using `lsblk` or `df`.
  2. Research the features and use cases of ext4, xfs, and btrfs.
  3. Identify the filesystem type used by your root partition.

## Exercise 2: Mounting and Unmounting Filesystems

- **Objective**: Practice mounting and unmounting filesystems.
- **Tasks**:
  1. Use the `mount` command to mount a USB drive and verify its contents.
  2. Unmount the USB drive using `umount` and ensure it is safely removed.
  3. Experiment with mounting a filesystem at boot by editing `/etc/fstab`.

## Exercise 3: Filesystem Management

- **Objective**: Learn to create, format, and check filesystems.
- **Tasks**:
  1. Use `mkfs` to format a partition with the ext4 filesystem.
  2. Check and repair a filesystem using `fsck`.
  3. Use `tune2fs` to modify filesystem parameters, such as the reserved block count.

## Exercise 4: Disk Partitioning

- **Objective**: Practice disk partitioning using various tools.
- **Tasks**:
  1. Use `fdisk` to create a new partition on a disk.
  2. Use `parted` to resize an existing partition.
  3. Explore `gparted` for a graphical interface to manage partitions.

## Exercise 5: Logical Volume Management (LVM)

- **Objective**: Explore the basics of LVM.
- **Tasks**:
  1. Create a physical volume using `pvcreate`.
  2. Create a volume group using `vgcreate` and add the physical volume to it.
  3. Create a logical volume using `lvcreate` and format it with a filesystem.
