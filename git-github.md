# Git und GitHub

Mithilfe von Git und GitHub können mehrere Leute gleichzeitig an einem Softwareprojekt arbeiten, ohne dass dabei irgendwelche Daten-Konflikte entstehen. 

Zwei YouTube Videos, die eine kurze Einführung geben:

- [https://youtu.be/3ZlpJHZBbi8](https://youtu.be/3ZlpJHZBbi8]) (Was ist Github?)
- [https://youtu.be/elh1y6laO8I](https://youtu.be/elh1y6laO8I) (Git Praxis Beispiel)

Hier eine kurze Anleitung, um in Git einzusteigen:
[https://thomas-leister.de/git-fuer-einsteiger/](https://thomas-leister.de/git-fuer-einsteiger/)

Weitere Ressourcen und Materialien:
- Sammlung von Materialien zu Git: [https://try.github.io/](https://try.github.io/)
- Offizielle Dokumentation von Git (sehr umfangreich): [https://git-scm.com/doc](https://git-scm.com/doc)
- Offizielle Ressourcen zu Github: [https://guides.github.com/](https://guides.github.com/)
- Offizielle Dokumentation von Github: [https://docs.github.com/en/free-pro-team@latest/github](https://docs.github.com/en/free-pro-team@latest/github)

Hier gibt es eine private Test-Repository, wo man die Funktionen von Git und GitHub ausproieren kann: [https://github.com/ahfs-gi/test-repository](https://github.com/ahfs-gi/test-repository)

## Das wichtigste komprimiert

### Befehle

- `git init` erstellt ein neues lokales Git Repository im aktuellen Verzeichnis.
- `git clone` kopiert ein Repository auf den eigenen Computer. Syntax: `git clone url`
- `git status` zeight den aktuellen Status eines Repositorys an (veränderte Dateien etc.)
- `git add` fügt Veränderungen zum nächsten Commit hinzu. Syntax: `git add Datei` oder `git add *` für alle Dateien.
- `git commit` erstellt eine neue veränderte "Version" des Projektes. Dabei muss eine Commit-Message angegeben werden, die die Veränderungen kurz zusammenfasst.
- `git push` lädt alle neue Commits auf den Server (GitHub) hoch.
- `git pull` lädt alle neue Veränderungen vom Server (GitHub) herunter.

### Workflow
1. `git pull` um die aktuellste Version vom Projekt herunterzuladen.
2. Änderungen am Code vornehmen.
3. `git add`
4. `git commit`

   Dabei eine kurze Zusammenfassung der Veränderungen in wenigen Worten angeben.
5. `git push` lädt neuen Commit hoch.
6. Zurück zu Schritt 1