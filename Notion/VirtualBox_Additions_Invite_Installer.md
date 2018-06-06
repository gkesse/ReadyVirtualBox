# Installer les additions invité de VirtualBox

Le but de cette section est de vous apprendre à installer les additions invité de VirtualBox.  
Produit par 
[Gérard KESSE](https://github.com/gkesse/ "https://github.com/gkesse").

# Insérer le CD des additions invité

![Image](https://raw.githubusercontent.com/gkesse/ReadyVirtualBox/master/Notion/img/Machine_Virtuelle_Additions_Invite_Configurer.png)

![Image](https://raw.githubusercontent.com/gkesse/ReadyVirtualBox/master/Notion/img/Machine_Virtuelle_Additions_Invite_Configurer_2.png)

# Procédure à suivre

* apt-get install build-essential
* apt-get install module-assistant
* m-a prepare
* mount /media/cdrom
* sh /media/cdrom/VBoxLinuxAdditions.run
* reboot
