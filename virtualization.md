# Virtualization

## Thumb rules
1. If you want to automate something, make sure you know how to do it manually

## Vagrant
- manages/automates VM lifecycle
- VM management with manual setup is time consuming and prone to errors
- no OS install, VM images/box available on Vagrant cloud
- Vagrantfile manage all vm settings in a file
- simple commands:
    * vagrant init boxname
    * vagrant up
    * vagrant ssh
    * vagrant halt
    * vagrant destroy

### Vagrant: steps for VM creation automation and useful commands
1. Create the VM with command
    * ```vagrant init eurolinux-vagrant/centos-stream-9```
2. List available VMs in current directory
    * ```vagrant box list```
3. Check if VM is running or not
    * ```vagrant status```
4. Log in to VM
    * ```vagrant ssh```
5. Poweroff the VM
    * ```vagrant halt```
6. Poweron the VM or create a new one if DNE
    * ```vagrant up```
7. Reboot the VM
    * ```vagrant reload```
8. Delete the VM
    * ```vagrant destroy```
9. Show all VM status
    * ```vagrant global-status```

### Additional Linux Commands
1. check the user
    * ```whoami```
2. log in to root user
    * ```sudo -i```
