# dhcpcdwaitfix
Prevent dhcpcd@.service from delaying boot if network connection is not available.
To install, move no-wait.conf to /etc/systemd/system/dhcpcd@.service.d/
