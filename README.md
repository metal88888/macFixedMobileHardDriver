# 解决macOS硬盘HFS+分区无法挂载问题
 1. ps aux | grep fsck
 2. sudo pkill -f fsck
 3. fsck_exfat -y -x /dev/disk2s2 
 4. diskutil mount /dev/disk2s2
