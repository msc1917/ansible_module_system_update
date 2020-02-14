# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "system_update"
System-Update, ausgegliedert da es beim Update via Ansible nahezu immer Probleme gibt

## Verzeichnis "defaults"
Standard-Variablen für die Rolle (werden von anderen Variabledefinitionen übersteuert)

## Definition der Parameter
Die unten angegebenen Parameter in Listen stellen die Parameter dar, die in den Rollen interpretiert werden.

### Settings für Hardware:
	hardware:
	  - wlan_5ghz
	  - wlan_24ghz
	  - bluetooth
	  - nfcDevice

### Settings für Software:
	software:
	  - git

### Settings für Services:
	services:
	  - ssh
	  - avahi
	  - xrdp

### Settings für das Enviroment:
	enviroment:
	  gui_system: false

### Settings für Development-Einstellungen:
	development:
	  get_git_repositories: true

### Settings für die hostfile-Erstellung ("/etc/hosts"):
	hostfile: 
	  create: true
	  full_hostfile: false

### Settings für Adaptionen am Linux-Kernel:
	kernel:
	  kernel_modules: true

### Settings für Machine-Learning-Engines:
	ml_engines:
	  - ncs
	  - coral
	  - jetpack

### Andere Parameter:
	do_mount_filesystems
	do_software_upgrade
	do_ansible

