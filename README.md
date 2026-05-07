# DVC-E1_new

Einsendeaufgabe DVC-E1: Versionsverwaltung mit Git

## 1. Repository erstellt

Ich habe ein eigenes öffentliches GitHub-Repository erstellt.

Repository:  
https://github.com/nost5746/DVC-E1_new

## 2. Eigenes Projekt hochgeladen

Ich habe ein kleines Beispielprojekt im Ordner `projekt` erstellt und hochgeladen.

Enthaltene Dateien:

- `projekt/app.py`
- `projekt/README-projekt.md`
- `projekt/variante-a.md`
- `projekt/variante-b.md`

## 3. Relevante Git-Methoden angewendet

Ich habe folgende Git-Methoden verwendet:

- `git status`
- `git diff --cached`
- `git add`
- `git commit`
- `git push`
- `git pull`
- `git mv`
- `git rm`
- `git log --oneline`

Beispielhafte Commit-Historie:

- `80cb2aa` Merge branch 'branch-variante-b'
- `8970f2b` Fuege Variante B hinzu
- `44e73f7` Fuege Variante A hinzu
- `9a6b6ed` Entferne temporaere Datei
- `dd79696` Fuege temporaere Datei hinzu
- `5be42fe` Benenne Projektbeschreibung um
- `5d6f3f6` Update README.md
- `ffbdcec` Fuege kleines Beispielprojekt hinzu
- `4c1e977` Initial commit

## 4. Zeitreisen

Ich habe mit `git log --oneline` die Commit-Historie angesehen.

Danach bin ich mit folgendem Befehl testweise zu einem älteren Stand gewechselt:

`git checkout HEAD~2`

Dabei war ich im sogenannten `detached HEAD`-Zustand.

Anschließend bin ich zurück zum aktuellen Stand gewechselt:

`git checkout main`

## 5. Branches und Merge

Ich habe zwei ähnliche Branches erstellt:

- `branch-variante-a`
- `branch-variante-b`

Ich habe zwischen den Branches gewechselt:

- `git checkout branch-variante-a`
- `git checkout branch-variante-b`
- `git checkout main`

Danach habe ich beide Branches wieder in `main` gemerged:

- `git merge branch-variante-a --no-edit`
- `git merge branch-variante-b --no-edit`

Die Branches wurden zusätzlich zu GitHub gepusht:

- `git push origin branch-variante-a`
- `git push origin branch-variante-b`

## 6. Pull Request zu edlich/education

Ich habe einen Pull Request zu `edlich/education` erstellt.

Pull Request:  
https://github.com/edlich/education/pull/594