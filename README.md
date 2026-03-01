# Ran – Reha App

PWA (Progressive Web App) für L5/S1 Rehabilitation.

## Setup – einmalig, dauert ~5 Minuten

### Schritt 1: Repository erstellen
1. Gehe zu github.com → "New repository"
2. Name: `recovery-app`
3. Public ✓
4. "Create repository"

### Schritt 2: Dateien hochladen
```bash
# Im Terminal (oder GitHub Desktop):
git clone https://github.com/Ranchuk7/recovery-app.git
cd recovery-app
# Alle Dateien aus diesem Ordner reinkopieren
git add .
git commit -m "Initial commit"
git push origin main
```

### Schritt 3: GitHub Pages aktivieren
1. Repository → Settings → Pages
2. Source: **GitHub Actions**
3. Speichern

### Schritt 4: Warten (~2 Minuten)
GitHub baut automatisch. Dann läuft die App unter:
**https://Ranchuk7.github.io/recovery-app/**

### Schritt 5: Auf Pixel installieren
1. Chrome öffnen → https://Ranchuk7.github.io/recovery-app/
2. Chrome-Menü (3 Punkte) → "Zum Startbildschirm hinzufügen"
3. "Installieren" → fertig!

Die App läuft jetzt wie eine native App, ohne Browser-Leiste.

## Updates
Wenn du die App aktualisieren willst: einfach `src/App.jsx` ändern und pushen. GitHub baut automatisch neu.
