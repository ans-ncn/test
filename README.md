# TYPO3 ncn Demo

# DDEV Erstinstallation
Vorraussetzung ist das DDEV bereits installiert ist ([Anleitung](https://ddev.readthedocs.io/en/stable/)).

Folgende Befehle im Terminal ausführen:
```bash
ddev start
ddev import-db --src=./dump.sql.gz
ddev composer install
```

# TYPO3 Zugang
## Frontend
Website aufrufen: http://typo3demo.ddev.site/

## Backend
Backend aufrufen: http://typo3demo.ddev.site/typo3/  
Benutzer: admin  
Passwort: honk-privet-jung