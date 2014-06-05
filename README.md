python-vmstats
==============

Python script using pyVmomi to get VM statistics

The script requires the following parameters:

-s HOST, --host HOST : Remote host to connect to.

-u USER, --user USER  : User name to use when connecting to host.

-p PASSWORD, --password PASSWORD : Password to use when connecting to host.

-m VM, --vm VM : Virtual Machine to report.

-i INT, --int INT : Interval to average the vSphere stats over in minutes


The -p/--password is now optional and if not provided on the command line will prompt instead.

http://www.geeklee.co.uk/2014/04/23/python-pyvmomi-get-vm-statistics-from-hypervisor/

http://www.geeklee.co.uk/object-properties-containerview-pyvmomi/
