# Linux Basics

- `passwd` can be used to update current user password.
- file permission is split into three groups `aaaabbbccc` where `aaaa` is owner permissions of the file, `bbb` is the group permissions of the file and `ccc` is the other users permissions for the file. There are 3 types of permissions `r` stands for `read` permission, `w` stands for `write` permission and `x` stands for `executable` permission. There is also `d` stands for `directory` and `t` stands for `temporary` directory.
- `chmod` can be used to change permissions of the file and directory. `chmod 777 filename` gives it all permissions.
- `/etc/passwd` has all the users list while `/etc/shadow` has the list of passwords
- `su` can be used to switch user with username and password.
- `ifconfig` and `iwconfig` can be used to list network adapters available on our system.
- `arp` can be used to see the mapping of IP addresses to MAC addresses.
- `>` replaces the content of the file while `>>` is used to append to the file.
- `mousepad` can be used to open file in mousepad file editor.
- `cat` can be used to to print out the content of the file.
- `python -m SimpleHTTPServer 8080` can be used to run a simple server at any directory.
- `service` can be used to start, stop and monitor services.
- `systemctl` can be used to run services on boot, etc.
- `apt-get update` will fetch all the updates list while `apt-get upgrade` will update the listed updates.
