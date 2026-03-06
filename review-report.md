# Handwerker & Blitz – Prüfbericht

## Was im hochgeladenen Archiv falsch war
- Im Archiv fehlten fast alle Dateien aus `images/portfolio/`; enthalten war nur `.gitkeep`.
- `portfolio.json` enthielt nur Demo-Einträge mit Beispielbildern wie `sample_kitchen_before.jpg`, die im Archiv gar nicht vorhanden waren.
- Dadurch konnten viele Portfolio-Bilder auf der Website nicht geladen werden.

## Was ich korrigiert habe
- Vollständige Portfolio-Bilder wieder in das Projekt eingebaut.
- `portfolio.json` neu aufgebaut: **28 Einträge für 28 Bilder**.
- Beschriftungen und Kategorien bereinigt und neutraler/formaler formuliert.
- Header-Logo und Hero-Logo auf die von dir hochgeladenen Dateien umgestellt.
- Logo-Darstellung verbessert, damit nichts abgeschnitten aussieht.
- Fehlende CSS-Regeln für die Cursor-Glow-Animation ergänzt.
- Paket von macOS-Müll bereinigt (`.DS_Store`, `__MACOSX`, `._...`).

## Projektstruktur
- `index.html`
- `styles.css`
- `script.js`
- `portfolio.json`
- `images/branding/logo-icon.png`
- `images/branding/logo-full.png`
- `images/portfolio/...` (28 Dateien)

## Wichtig
Wenn du dieses Paket neu auf GitHub hochlädst, ersetze den alten Stand komplett durch dieses Projekt.
