# Git uff Barlinerisch

Fuer die tägliche Kommunikation in deutschen Entwicklungsteams, die `git`
(übersetzt: `Demelsack` oder `Depp`) anwenden, ist oft das feinste Denglish.
_"Kannste mal pullen, wa"_ oder _"Haste schon gepusht"_ sind nur zwei
der oft seltsam klingenden Konstruktionen.

"git" uff Barlinerinsche schafft Abhilfe!

## Vorschläge

Es folgen zwei Tabelln mit Vorschlägen für den täglichen Gebrauch.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initten            | uffmachen             |
| add         | adden              | rinnmachen            |
| blame       | blamen             | petzen                |
| pull        | pullen             | zieh                  |
| push        | pushen             | schieb                |
| clone       | clonen             | nachaeffen            |
| fetch       | fetchen            | hol                   |
| branch      | branchen           | abbiegen              |
| commit      | commiten           | einbuchen             |
| rebase      | rebasen            | (neu) erden           |
| diff        | diffen             | unterscheiden         |
| merge       | mergen             | vereinigen            |
| fork        | forken             | abbiegen              |
| stash       | stashen            | verstauen             |
| tag         | taggen             | markieren             |
| cherry-pick | cherry-picken      | Rosinen stibitzen     |
| checkout    | checkouten         | ausbuchen             |
| squash      | squashen           | quetschen             |

Hier noch einige (zum Teil nicht ganz ernste)

| Substantiv    | Aktueller Gebrauch | Vorschlag                  |
|---------------|--------------------|----------------------------|
| git           | git                | Atze                       |
| github        | github             | Atzenkietz                 |
| gitlab        | gitlab             | Atzenlabor                 |
| gitea         | gitea              | Atzentee                   |
| blame         | blame              | petzen                     |
| bitbucket     | gitbucket          | Jebisseimer                |
| repository    | repo               | Depot                      |
| branch        | branch             | Zweig                      |
| commit        | commit             | Einbuchung                 |
| log           | log                | Tagebuch                   |
| pull request  | pull request       | Ziehbegehren               |
| merge request | merge request      | Antrag auf Zusammenführung |
| stash         | stash              | Versteck                   |
| status        | status             | Zustand                    |
| tag           | tag                | Markierung                 |
| origin        | origin             | Ursprung                   |
| master        | master             | Meister                    |
| main          | main               | Haupt                      |

## Beispiele

    - Kannste mal den Zweig, den icke gerade umgeschrieben habe, ziehen und zum Atzenkietz drücken? 

    - Dafür hab icke ein neues Depot uffgemacht, aeff ditte mal nach und nimm dir mal den Entwicklerzweig.

    - Nee, ditte drückste mal gleich zum Meister im Ursprung!
    
    - Dit kannste im Kietzanschwaerzer sehen, welches Ihmchen ditte jemacht hat.

    - Icke bin gerade abgezweigt und hab die Änderungen aus menem Bunker jeholt.

    - Mach da mal Ziehbegehren uff, wenn de mit dener Vereinigung fertig bist, wah!

    - icke stibitz uns mal die Rosinen aus dem Hauptzweig heraus, wah !

    - gabeln wir ditte mal uff den Atzenkietz!
    
    - Wenn du fertig bist, dann kannst du das Ziehbegehren sofort quetschen und zusammenführen.

## Depp auf Berlinerisch anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Depp auf Deutsch in Deine Konsole bringt. Da Depp keine Umlaute zulässt, müssen wir in den Befehlen leider darauf verzichten. Nimm folgende Änderungen in deiner `~/.gitconfig` vor:

    git config --global alias.uffmachen init
    git config --global alias.nachaeffen clone
    git config --global alias.zieh pull
    git config --global alias.rinnmachen add
    git config --global alias.drueck push
    git config --global alias.pfusch 'push --force'
    git config --global alias.zweig branch
    git config --global alias.verzweige branch
    git config --global alias.buche-ein commit
    git config --global alias.erde rebase
    git config --global alias.unterscheide diff
    git config --global alias.vereinige merge
    git config --global alias.bunkere stash
    git config --global alias.markiere tag
    git config --global alias.buche-aus checkout
    git config --global alias.tagebuch log
    git config --global alias.zustand status
    git config --global alias.petzen blame

Und füge die folgende Zeile zu deiner `~/.bashrc` (oder das Äquivalent auf deinem Betriebssystem) hinzu:

    alias atze=git
https://github.com/danielauener/git-auf-deutsch.git
