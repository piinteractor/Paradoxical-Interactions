# Github Upload Anleitung

## Voraussetzungen
- Github Account
- Git installiert (bereits vorhanden)

## Schritte zum Hochladen

### 1. Neues Repository auf Github erstellen
1. Gehe zu https://github.com/new
2. Repository Name: `piinteract-vault` (oder anderer Name)
3. Beschreibung: "Obsidian vault with complete piinteract.org content structure"
4. Public oder Private wählen
5. **WICHTIG:** Keine README, .gitignore oder License hinzufügen (haben wir schon)
6. "Create repository" klicken

### 2. Lokales Repository mit Github verbinden

Öffne ein Terminal im Vault-Verzeichnis und führe aus:

```bash
cd /mnt/user-data/outputs/piinteract-vault

# Remote hinzufügen (ersetze USERNAME mit deinem Github-Username)
git remote add origin https://github.com/USERNAME/piinteract-vault.git

# Branch umbenennen falls nötig
git branch -M main

# Hochladen
git push -u origin main
```

### 3. Alternative: Mit Github CLI

Falls du Github CLI installiert hast:

```bash
cd /mnt/user-data/outputs/piinteract-vault
gh repo create piinteract-vault --public --source=. --remote=origin --push
```

### 4. Nach dem Upload

Das Repository ist dann verfügbar unter:
`https://github.com/USERNAME/piinteract-vault`

## Branch-Strategie

Der Code ist bereits im `main` Branch committed. Wenn du einen anderen Branch-Namen bevorzugst:

```bash
git branch -m main dein-branch-name
git push -u origin dein-branch-name
```

## Vault-Struktur

```
piinteract-vault/
├── README.md              # Einführung für Besucher
├── INDEX.md               # Navigation für Obsidian
├── GITHUB_README.md       # Diese Datei (für Github Repo)
├── .gitignore
├── .obsidian/
│   └── app.json
├── Framework/
│   └── Framework.md
├── Examples/
│   ├── Examples.md
│   ├── Systems-Governance/
│   ├── Technology-AI/
│   ├── Organizations/
│   ├── Society-Culture/
│   └── Science-Academia/
└── Practices/
    ├── Practices.md
    ├── Core-Practices/
    ├── Anti-Practices/
    └── Scenarios/
```

## Repository Einstellungen (optional)

Nach dem Upload auf Github:

1. Gehe zu Repository Settings
2. Füge Topics hinzu: `obsidian`, `knowledge-management`, `systems-thinking`, `paradox`
3. Aktiviere Github Pages (Settings > Pages) für eine Web-Version
4. Füge eine LICENSE-Datei hinzu wenn gewünscht

## Klonen für andere Nutzer

Andere können das Vault klonen mit:

```bash
git clone https://github.com/USERNAME/piinteract-vault.git
cd piinteract-vault
# In Obsidian öffnen: "Open folder as vault"
```

---

**Nächste Schritte nach Upload:**
- GITHUB_README.md → README.md umbenennen für Github
- Links im Repository prüfen
- About-Sektion auf Github ausfüllen
- Ggf. weitere Dokumentation hinzufügen
