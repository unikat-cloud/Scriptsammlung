# Hinweise

## Windows
- Das Script benötigt Laufwerke mit entsprechenden Zugriffsrechten.
- Für detaillierte Informationen müssten ggf. zusätzliche Module installiert werden.
- Du kannst den `$exportPath` anpassen, wo die Datei gespeichert werden soll.

## Linux
- Das Script benötigt root-Rechte, da `dmidecode` meist nur mit `sudo` ausgeführt werden kann.
- Für einige Befehle (z.B. `dmidecode`) muss das Paket installiert sein:

```bash
sudo apt update
sudo apt install dmidecode
```

- Die Tools wie `lscpu`, `lsblk`, `ip`, `lspci` sind in den meisten Linux-Distributionen standardmäßig enthalten.
- Das Script schreibt alle Daten in eine Datei im Heimatverzeichnis (`~/Hardware_Inventar.txt`).
