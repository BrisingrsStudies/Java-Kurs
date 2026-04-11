# Java Kurs – Azubi Lernbegleiter

Interaktiver Java-Kurs für Azubis der Anwendungsentwicklung, basierend auf der [roadmap.sh Java-Roadmap](https://roadmap.sh/java) und dem Buch **„Java ist auch eine Insel"** von Christian Ullenboom.

## Features

- **59 Lektionen** in 8 Phasen – von Grundlagen bis Clean Code
- **Sofortige Antworten** – alle Inhalte sind eingebettet, kein Internet nötig
- **Buchverweise** – jede Lektion zeigt das passende Kapitel aus „Java ist auch eine Insel"
- **Fortschrittsanzeige** – markiere Lektionen als erledigt (wird lokal gespeichert)

## Lernpfad

| Phase | Thema | Lektionen |
|-------|-------|-----------|
| 1 | Grundlagen | 12 |
| 2 | Objektorientierung (OOP) | 9 |
| 3 | Fortgeschrittene Konzepte | 13 |
| 4 | Werkzeuge & Build | 7 |
| 5 | Datenbanken & SQL | 4 |
| 6 | Spring Framework | 6 |
| 7 | Testing | 4 |
| 8 | Clean Code & Patterns | 4 |

## GitHub Pages einrichten

### Schritt 1 – Repository erstellen

```bash
# Lokal
git init java-kurs
cd java-kurs
# index.html und README.md reinkopieren
git add .
git commit -m "feat: Java Lernbegleiter initial"
```

### Schritt 2 – Auf GitHub hochladen

```bash
git remote add origin https://github.com/DEIN-NAME/java-kurs.git
git push -u origin main
```

### Schritt 3 – GitHub Pages aktivieren

1. Gehe zu deinem Repository auf GitHub
2. Klicke auf **Settings** → **Pages**
3. Unter **Source**: Branch `main`, Ordner `/ (root)` wählen
4. Klicke **Save**

Nach ca. 1 Minute ist die App unter folgender URL erreichbar:

```
https://DEIN-NAME.github.io/java-kurs/
```

### Updates deployen

```bash
# Änderungen committen und hochladen
git add .
git commit -m "fix: ..."
git push
# → GitHub Pages aktualisiert sich automatisch
```

## Lokal testen

Da die App komplett statisch ist, kannst du sie einfach lokal öffnen:

```bash
# Option 1: Direkt im Browser öffnen
open index.html   # macOS
start index.html  # Windows

# Option 2: Lokaler Webserver (empfohlen)
python3 -m http.server 8080
# → http://localhost:8080
```

## Referenz

- Buch: **Java ist auch eine Insel** – Christian Ullenboom, Rheinwerk Verlag, 14. Auflage 2019
- Roadmap: [roadmap.sh/java](https://roadmap.sh/java)
