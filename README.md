# Desktop initialisation script
To be run after full Ubuntu Gnome reinstall. 3 parts, you can customize and complete for your needs.

## APT-GET packages
Script installs Git, Git Flow, apache2, php5, mysql-server, php5-mysql, phpmyadmin, terminator, filezilla, vlc, browser-plugin-vlc, owncloud-client, revelation, default-jre, default-jdk. **Just add packages to packages variable array**. The script use a loop with graphical display to follow progression.

## Stand-alone software
Script installs latest Google Chrome Version, Skype, HPLIP (for HP printers). For each of them, **the script checks if package already installed before any command**.

## Set favorites
Scripts override default Gnome favorites with some of the softwares above. Fell free to change in order to suit your needs.


Usage (dead simple, just make sure you're in the script directory) :
  `bash desktop-initialisation-script`
