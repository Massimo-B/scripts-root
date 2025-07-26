Collection of unsorted scripts for user root

### defrag_btrfssnapshot
Defragmentation of a target snapshot (btrfs RO snapshot) without modification or breaking parent relations, applying defragmentation to all sibling snapshots

### dmcrypt
Open or close dmcrypt device

### find-luks
Tries to find a LUKS header on a damaged/deleted/overwritten blockdevice

### update_btrbksnapshotlinks
All btrbk snapshot (variable "snapshot_dir") and target dirs (variable "target") are parsed from
configuration file in order to add a "latest ->" symlink pointing to the latest snapshot.
