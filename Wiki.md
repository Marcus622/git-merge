# Technische Begriffe

Git ist ein verteiltes Versionskontrollsystem, das von Entwicklern verwendet wird, um den Verlauf von Projekten zu verfolgen und mit anderen zusammenzuarbeiten. Hier sind die wichtigsten Begriffe, die du in Git kennen solltest:

### 1. **Repository (Repo)**
   - Ein Repository ist der zentrale Ort, an dem alle Dateien und der gesamte Verlauf eines Projekts gespeichert sind. Es kann lokal auf deinem Computer oder auf einem Server (wie GitHub) gehostet werden.

### 2. **Commit**
   - Ein Commit ist eine Änderung oder ein "Snapshot" deines Projekts. Jedes Commit speichert eine Version deines Projekts und enthält eine Nachricht, die beschreibt, was geändert wurde. Du kannst Änderungen committen, um den Verlauf des Projekts zu dokumentieren.

### 3. **Branch**
   - Ein Branch (Zweig) ist eine parallele Version eines Projekts. Du kannst einen neuen Branch erstellen, um an einer Funktion oder Bugfix zu arbeiten, ohne den Hauptzweig zu beeinflussen. Der Hauptbranch heißt oft `main` oder `master`.

### 4. **Merge**
   - Merge ist der Vorgang, bei dem die Änderungen von einem Branch in einen anderen integriert werden. Zum Beispiel wird ein Feature-Branch in den Haupt-Branch zusammengeführt, wenn die Arbeit abgeschlossen ist.

### 5. **Clone**
   - Mit `git clone` erstellst du eine Kopie eines bestehenden Git-Repositories. Dies ist besonders nützlich, wenn du ein Projekt von einem Remote-Server (z. B. GitHub) herunterladen möchtest.

### 6. **Pull**
   - Mit `git pull` ziehst du die neuesten Änderungen aus einem Remote-Repository und fügst sie in dein lokales Repository ein. Dies ist nützlich, um die Arbeit anderer Entwickler zu integrieren.

### 7. **Push**
   - Mit `git push` sendest du deine lokalen Commits an ein Remote-Repository, sodass andere Entwickler auf deine Änderungen zugreifen können.

### 8. **Remote**
   - Ein Remote ist eine Version eines Repositories, die auf einem Server (wie GitHub, GitLab, Bitbucket) gespeichert wird. Du kannst mit dem Remote-Repository interagieren, um Änderungen zu synchronisieren.

### 9. **Staging Area**
   - Die Staging Area ist der Bereich, in dem du Änderungen vorbereitest, bevor du sie commitest. Mit `git add` fügst du Dateien zur Staging Area hinzu.

### 10. **HEAD**
   - HEAD ist ein Zeiger auf den aktuellen Commit in deinem lokalen Repository. Wenn du einen Branch wechselst, bewegt sich HEAD zu diesem Branch.

### 11. **Diff**
   - Ein `git diff` zeigt die Unterschiede zwischen zwei Versionen von Dateien oder Branches an. Dies hilft dir, Änderungen nachzuvollziehen.

### 12. **Tag**
   - Ein Tag ist ein Markierungspunkt, der oft für wichtige Meilensteine oder Releases verwendet wird, um eine spezifische Version des Projekts zu kennzeichnen.

### 13. **Rebase**
   - `git rebase` ist eine Möglichkeit, Commits aus einem Branch auf einen anderen Branch zu übertragen. Es hilft, eine saubere Historie zu erhalten, indem es die Reihenfolge der Commits ändert.

### 14. **Fork**
   - Ein Fork ist eine Kopie eines Repositories, die von einem anderen Benutzer erstellt wird. Ein Fork ermöglicht es dir, Änderungen zu einem Repository vorzuschlagen, ohne direkten Zugriff darauf zu haben (häufig verwendet auf GitHub).

### 15. **Pull Request (PR)**
   - Ein Pull Request (oder Merge Request) ist eine Anfrage, um Änderungen von einem Branch (normalerweise einem Fork) in einen anderen Branch (meistens in das Original-Repository) zu integrieren.

### 16. **Conflict**
   - Ein Konflikt tritt auf, wenn zwei Branches Änderungen an der gleichen Datei an denselben Stellen vorgenommen haben. Git kann diese Änderungen nicht automatisch zusammenführen, und der Entwickler muss den Konflikt manuell lösen.

Diese Begriffe decken die grundlegenden Konzepte in Git ab und helfen dir, effizient mit dem System zu arbeiten. Wenn du ein tieferes Verständnis entwickeln möchtest, kannst du mit diesen Grundlagen experimentieren, indem du kleine Projekte in Git verwaltest!
