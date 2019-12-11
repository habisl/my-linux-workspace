Shell is an interface between the user and the kernel
common shells are. 
- bash
- csh
- ksh

$ - for regular user

'#' - is for root user


# ls #

ls -l : List files in the current directory with detailed info

[root@internal ~]# ls -l
total 6797952
drwx------. 2 root    root         4096 Sep 21  2018 ansible
-rwx------. 1 root    root    205832192 Jan 30  2019 api-gateway-backup.tar
-rwx------. 1 root    root    205832192 Sep 15 20:28 api-gateway.tar

permissions, Links, Owner(user), Group owner, size, Month, Day, Time, Filename

ls –lh  To list files in the current directory with their size in human readable format.

ls –lt  To list files in the current directory with detailed info sorted by date and time with the newest file first.

ls –ltr To list files with detailed info sorted by date and time with the newest file first in reverse order.

ls –F   Shows you the file types – (/=dir), (@=link) and (*=executable).

ls -la  To list all files including the hidden files with detailed info.
