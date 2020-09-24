CheckDisk
====

This script uses smartctl to grab SMART disk attributes and inform the 
the user if certain attrubutes have non-sero values - which may indicate
that the disk should be replaced. The concept is inspired by a 
[Backblaze blog article](https://www.backblaze.com/blog/what-smart-stats-indicate-hard-drive-failures/).

This uses a POSIX shell and has been tested with FreeBSD sh and bash.
