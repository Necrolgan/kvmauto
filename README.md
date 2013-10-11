kvmauto
=======

Auto Starter for KVM/QEMU - Virsh based Virtual Machines


Installation:
Edit etc.default.startvms to suit your requirments then run:

 * sudo cp usr.bin.startvms /usr/bin/startvms
 * sudo chmod 755 /usr/bin/startvms
 * sudo cp etc.default.startvms /etc/default/startvms
 * sudo cp etc.init.startvms.conf /etc/init/startvms.conf
 

And that's the ball... reboot and the daemon will boot your Virutals in the timing and order set out in /etc/default/startvms

Format usage is shown in default file.
