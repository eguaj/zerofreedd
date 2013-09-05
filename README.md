zerofreedd
==========

Fill up file-system' free space with zero.

Suitable for shrinking VMs' disks.

Example:

    (guest)# zerofreedd /data
    Zeroing 1234MB in '/data/zerofreedd.2z5vg6'...
    Done.

    (host)# VBoxManage /path/to/your-guest-data-disk.vdi --compact
    0%...10%...20%...30%...40%...50%...60%...70%...80%...90%...100%

