# note_systemctl-chkconfig
chkconfig and systemctl

chkconfig command does not support anymore. It is replaced by systemctl

# List processes
```sh
# chkconfig --list
# systemctl list-units
```

# Automaticly start the service in linux when reboot
```sh
# chkconfig <servicename> on
# chkconfig <servicename> on
```
  
# Stopping the service starting in linux when reboot
```sh
# chkconfig <servicename> off
# systemctl disable <servicename>.service
```
# Start the service
```sh
# service <servicename> start
# systemctl start <servicename>.service
```
# Stop the service
```sh
# service <servicename> stop
# systemctl stop <servicename>.service
```
# Check the status of the service
```sh
# service <servicename> status
# systemctl status <servicename>.service
```


[PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
