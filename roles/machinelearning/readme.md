# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "machinelearning"
Einrichten der Hosts für Machinelearning-Tools (Google Coral, Intel NCS und nvidia Jetpack)

## Verzeichnisse:
* tasks: Playbook-Tasks, welche in der Rolle durchgeführt werden
* handlers: Ansible-Handler-Definitionen
* meta: Meta-Daten für die Rolle
* defaults: Standard-Variablen für die Rolle (werden von anderen Variabledefinitionen übersteuert)
* vars: Weitere Variablen für die Rolle
* templates: Jinja2-Templates, welche von der Rolle benötigt werden könnten
