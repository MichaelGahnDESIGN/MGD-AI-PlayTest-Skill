# AI-PlayTest-Skill
Dieser Skill führt einen PlayTest durch der die von KI Agenten erstellte Funktionen testet.

- /playtest startet einen lokalen Playtest
- /playtest-live startet einen Play-Test in der Live-Umgebung.

#Ablauf:

1. Ein Abafrage Assistent startet und fragt ob er einen Play-Test Ordner erstellen soll falls noch keiner besteht und wo.

2. Ein Playtest unterordner nach dem Schema /PLAYTEST/Playtest-live_DD-MM-YYYY-X wird im Prohejtordner erstellt.

3. Der Play-Test schreibt folgende Dateien:

- Test-Aufgabe.md (Liste der TEst-Aufträge)
- Test-Protokoll.md (Protokoll aller getesteter Funktionen und des ablaufes)
- Test-Auswertung.md (Hier beschriebt der Agent das Ergebnis seiner Tests)
- Test-Bugfix.md (Eine Liste aller gefundenen Issues)
- Test-Todo.md (Eine Liste was nach dem PalyTest zu tun ist)
- Test-Verbesserungsvorschlaege.md (Ideen der AI Was man optimieren kann)

4. Der Agent startet eine Abfrage und stellt nacheinander folgende Fragen:

  - Was teste ich? (App / Editor / Website / ...)
  - Existiert Playtest oder Playtest-Live Ordner schon oder soll ich anlegen?
  - benötigte Zugangsdaten (zum Beispiel für Test-Email-SMTP oder Test-Login Daten oder ...)
- Rolle? (soll der Test aus sicht eines Nutzers, Admin, Spielers, .... statt finden?)
- Agenten nutzen? (Beispielsweise um Inetraktionen verscheidener Nutzer über Agenten zu simulieren)
- Logische Fragen (zum Beispiel: Besuche ich die Seite / App /... zum ersten Mal? Kenne ich sie schon?, ...)
- Ablauf Checkliste (welche Dinge sollen getestetet werden?


5. Der Agent erstellt passende Agenten / Sub-Agenten

6. Während des Playtest oder Live-Playtest macht der Agent Notizen was geht und was nicht geht, welche Verbesserungen er hat usw und notiert alles in den angelegten .md Dateien

7. Am Ende gibt Dir der Agent eine Übersicht der Dateien und eine Liste der Testergebnisse.

# Agents
Dieser Skill wurde in ChatGPT Codex und Clade Cowork sowie Claude Code getestet.
Der Skill veröffentlicht oder speichtert keine Sensiblen Daten und der Ordner PLAYTEST und alles darin bekommt .gitignore und verbleibt immer nur lokal.

# Beispiel Ablauf:

Live-Test von DungeonJournal.com 
/playtest-live (Erstellt einen Ordner "PLAYTEST" Ordner mit entsprechendem Unterordner und darin eine Test-Aufgabe.md , eine Test-Protokoll.md , eine Test-Asuwertung.md und eine Test-Todo.md und eine Test-Bugfix.md und eine Test-Verbesserungsvorschlaege.md

hier smb://000.000.000/Obsidian/Ordner/App/Spiel/Passswort.md da sind Email Zugangsdaten.

Tu so als wärst Du ein erfahrener Spieler, der von [Spiel-App-Name] gehört hat aber es nicht kennt.

Du willst es als Spieler in einer Gruppe nutzen.

Du nutzt die App [Spiel-App-Name] zum ersten mal. Du hast Spielerfahrung und Nutzerfreundlichkeit, ischerheit und Ästhetik sind Dir besonders wichtig.

Registriere dich. Dafür hast Du diesen Invation-Code: DJ-3997-13F8-9BC8 (10x nutzbar)

- Du siehst [Spiel-App-Name] zum ersten Mal.
- Du willst dich mit 2 Freunden verbinden und eine Gruppe bilden.
- Du willst Dir einen Charakter (Ork Magier) erstellen (genau wie deine Freunde sich beliuebige CHaraktere erstellen)
- Du willst deine Zauber zuweisen und spielst eine Runde mit deinen Freunden.
- Du willst zaubern.
- Deine Freunde werden angegriffen, Hilf ihnen!
- Du willst dein Inventar ansehen.
- Du erreichst Level 2.
- Ihr beendet die Session und spielt irgend wann wieder.

----------

Die KI diese Funktionen in der Rolle die Du ihr gegeben hast und nutzt eventuell passende Agenten / Sub-Agenten als Freunde.
Am Ende erhältst Du eine Auswertung.

# Lizenz
MIT Lizenz

#Impressum

Angaben gemäß § 5 DDG (Digitale-Dienste-Gesetz)

Michael Gahn DESIGN
Michael Gahn
Dr.-Theodor-Brugsch Str. 12
08529 Plauen
Sachsen
Deutschland

Tel.: +49 (0) 176 557 647 48
E-Mail: Anfrage@Michael-Gahn.de

Umsatzsteuer-Identifikationsnummer gemäß §27 a Umsatzsteuergesetz:
Steuernummer: 223/222/02451
Ust-ID: DE288143343
