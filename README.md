# MyFileSystem

A UnixV6-like file system

* The compile instruction: `clang++ src/*.cpp -o MyFileSystem`

* The normal use of 'tree' command requires the terminal to be set to the utf8 character set instead of gbk or gb2312 character set. 

* The inode of the filesystem has 6 direct pointers, 2 single indirect pointers, and 2 double indirect pointers. 

* The blocks of the disk is managed by **group link method**. 

* This filesystem has a caching machanism.


