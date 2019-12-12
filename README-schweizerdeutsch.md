# Git uf Schwiizerdütsch

Di täglich komunikation i schwiizer entwicklerteams, wo `git` (übersetz: `Dubbel` oder `Spasst`) verwendet wird, isch immer perfekts denglish im isatz.
_"Chasch bitte pullä"_ oder _"Häsch scho pushed"_ sind nur zwei vo vielne seltsam tönende sätz.

Git uf Schiizerdütsch hilft!

## Vorschläg

Es sind folgendi zwei Tabelle mit Vorschläg für de täglich Gebruch.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initten            | ufmache               |
| add         | adden              | dri tue            |
| blame       | blamen             | täderle        |
| pull        | pullen             | riisse                |
| push        | pushen             | schupfe              |
| clone       | clonen             | nachmachen            |
| fetch       | fetchen            | füre hole                 |
| branch      | branchen           | abbüge             |
| commit      | commiten           | verspräche             |
| rebase      | rebasen            | (neui) ärde           |
| diff         | diffen              | unterscheiden         |
| merge       | mergen             | zusammenführen        |
| fork        | forken             | abspalten             |
| stash       | stashen            | verstecken            |
| tag         | taggen             | markieren             |
| cherry-pick | cherry-picken      | Rosinen herauspicken  |
| checkout    | checkouten         | nehmen                |

Da na es paar meh

| Substantiv    | Aktueller Gebrauch | Vorschlag                  |
|---------------|--------------------|----------------------------|
| git           | git                | Dubbel                       |
| github        | github             | Dubbelzentrum            |
| gitlab        | gitlab             | Dubbellabor                |
| gitea         | gitea              | Dubbeltee                  |
| blame         | blame              | Deppenbeschuldigung        |
| bitbucket     | bitbucket          | Gebisseimer                |
| repository    | repo               | Lagerstätte                |
| branch        | branch             | Zweig                      |
| commit        | commit             | Übergabe                   |
| log           | log                | Tagebuch                   |
| pull request  | pull request       | Ziehbegehren               |
| merge request | merge request      | Antrag auf Zusammenführung |
| stash         | stash              | Versteck                   |
| status        | status             | Zustand                    |
| tag           | tag                | Markierung                 |
| origin        | origin             | Ursprung                   |
| master        | master             | Meister                    |

## Biispil

    - Kannst du den Zweig, den ich gerade umgeschrieben hab, ziehen und zum Deppendrehkreuz drücken?

    - Dafür habe ich eine neue Lagerstätte eröffnet, mach sie nach und nimm dir den Entwicklungszweig.

    - Nein, drücke das gleich zum Meister im Ursprung!
    
    - Du kannst in der Deppenbeschuldigung sehen, wer das geändert hat.

    - Ich hab gerade abgezweigt und die Änderungen aus meinem Versteck übergeben.

    - Mach ein Ziehbegehren, wenn du mit der Vereinigung fertig bist!

    - Am besten wir picken uns die Rosinen aus dem Meisterzweig heraus.

    - Gabeln Sie auf Deppendrehkreuz!

## Dubbel uf Schwiizerdütsch ahwende

Wer de nächsti Schritt mache wott, da e chlini Ahleitig, zum Dubbel uf Schwiizerdütsch i dini Konsole z bringe. Da de Dubbel kei Umlut zuehlah, münd mer i de Befehl leider druf verzichte. Nimm die folgendi Änderige i dim `~/.gitconfig` vor:

    git config --global alias.eroeffne init
    git config --global alias.machnach clone
    git config --global alias.zieh pull
    git config --global alias.fueghinzu add
    git config --global alias.drueck push
    git config --global alias.pfusch push --force
    git config --global alias.zweig branch
    git config --global alias.verzweige branch
    git config --global alias.uebergib commit
    git config --global alias.erde rebase
    git config --global alias.unterscheide diff
    git config --global alias.vereinige merge
    git config --global alias.bunkere stash
    git config --global alias.markiere tag
    git config --global alias.nimm checkout
    git config --global alias.tagebuch log
    git config --global alias.zustand status
    git config --global alias.beschuldige blame

Und füge die folgende Zeile zu deiner `~/.bashrc` (oder das Äquivalent auf deinem Betriebssystem) hinzu:

    alias dubbel=git
https://github.com/danielauener/git-auf-deutsch.git
