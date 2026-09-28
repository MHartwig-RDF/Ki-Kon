# KI-Kon Kurs

Online-Kurs für das Fach Künstliche Intelligenz Konzepte (KI-Kon), Rudolf-Diesel-Fachschule Nürnberg.

## Aufbau

```
index.html              ← Kursübersicht (Startseite)
b1-ki-zyklus/index.html ← Einheit B 1: KI-Werkstatt Predictive Maintenance
```

Jede Einheit ist ein eigener Ordner mit einer `index.html`.

## Neue Einheit ergänzen

1. Neuen Ordner anlegen, z. B. `b2-objekterkennung/`, und die `index.html` der Einheit hineinlegen.
2. In der `index.html` im Hauptordner (Kursübersicht) den Eintrag der Einheit in der Liste `EINHEITEN` ergänzen bzw. bei `ordner` den Ordnernamen eintragen.
3. Wichtig: Jede Einheit braucht in ihrem Code einen **eigenen Speicherschlüssel** (Zeile `const KEY='…'`), sonst überschreiben sich die gespeicherten Schülerantworten gegenseitig.
