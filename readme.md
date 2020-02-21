# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "system_update"
System-Update, ausgegliedert da es beim Update via Ansible nahezu immer Probleme gibt

## Verzeichnisse:
* **tasks:** Playbook-Tasks, welche in der Rolle durchgeführt werden
* **handlers:** Ansible-Handler-Definitionen
* **meta:** Meta-Daten für die Rolle
* **defaults:** Standard-Variablen für die Rolle (werden von anderen Variabledefinitionen übersteuert)
* **vars:** Weitere Variablen für die Rolle
* **files:** Files, welche von der Rolle benötigt werden könnten
* **templates:** Jinja2-Templates, welche von der Rolle benötigt werden könnten
