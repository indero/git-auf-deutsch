# Git auf Deutsch (Zürcher-Schwizerdütsch)

Die täglichi Kommunikation i schwiizer Entwicklerteams, wo `git` (übersetzt: `Tubel` oder `Löli`) awended, isch oft sehr usprägts Denglisch.
_"Chasch bitte pulle"_ oder _"Häsch pusht?"_ sind nur zwei vo de of komisch klingende Konstruktionä.

Git uf Dütsch schafft Abhilf!

## Vorschläg

Es folged zwei Tabelle mit Vorschläg zum tägliche Gebruch.

| Verb        | Aktueller Gebrauch | Vorschlag       |
| ----------- | ------------------ | --------------- |
| init        | initten            | uf mache        |
| add         | adden              | hinzufüge       |
| pull        | pullen             | zie             |
| push        | pushen             | drucke          |
| clone       | clonen             | namache         |
| fetch       | fetchen            | hole            |
| branch      | branchen           | abzwige         |
| commit      | commiten           | übergä          |
| rebase      | rebasen            | (neu) erde      |
| diff        | diffen             | vergliche       |
| merge       | mergen             | vereinige       |
| fork        | forken             | gable           |
| stash       | stashen            | bunkere         |
| tag         | taggen             | markiere        |
| cherry-pick | cherry-picken      | Rosine usepicke |
| checkout    | checkouten         | nää             |

| Substantiv | Aktueller Gebrauch | Vorschlag       |
| ---------- | ------------------ | --------------- |
| git        | git                | Löli            |
| github     | github             | Löliendrähchrüz |
| gitlab     | gitlab             | Lölilabor       |
| gitea         | gitea              | Lölitee |
| bitbucket     | bitbucket          | Gebisschübel    |
| repository    | repo               | Lagerstätte       |
| branch        | branch             | Zwiig             |
| commit        | commit             | Übergab             |
| log           | log                | Tagebuch             |
| pull request  | pull request       | Ziehbegehrä      |
| merge request | merge request      | Vereinigungsbegehrä |
| stash         | stash              | Bunker            |
| status        | status             | Zuestand             |
| tag           | tag                | Markierig       |
| origin        | origin             | Ursprung             |
| master        | master             | Meischter      |

## Beispiele

    - Chasch du de Zwiig, wo ich gad umgschribe ha, ziä und zum Lölidrähchrüz druckä?
    
    - Dafür hani e neui Lagerstätti eröffnet, mach si na und nimm der de Entwickligszwiig.
    
    - Nei, druck das gad zum Meister im Ursprung.
    
    - Ich ha gad abzwigt und d'Änderig us mim Bunker übergä.
    
    - Mach es Ziehbegehrä, wenn mit em Vereinigä fertig bisch.
    
    - Am beste picke mer eus d'Rosine usem Meischterzwiig use.
    
    - Gabläd Sie eus ufem Lölidrächrüz!

## Löli auf Schwizer-Dütsch anwenden

Wer de nögscht Schritt mache will, da e Aleitig, de Löli uf Dütsch i dini Konsole z'bringe. Da Löli kei Umlut zuelat, müemer i de Befehl leider druff verzichte. Nimm folgendi Änderig i dinere `~/gitconfig` vor:

    git config --global alias.ufmache init
    git config --global alias.namache clone
    git config --global alias.zie pull
    git config --global alias.hinzuefuege add
    git config --global alias.druck push
    git config --global alias.pfusch push --force
    git config --global alias.zwiig branch
    git config --global alias.verzwige branch
    git config --global alias.uebergib commit
    git config --global alias.erde rebase
    git config --global alias.vergliich diff
    git config --global alias.vereinige merge
    git config --global alias.bunkere stash
    git config --global alias.markiere tag
    git config --global alias.nimm checkout
    git config --global alias.tagebuech log
    git config --global alias.zuestand status

Und füeg folgendi Zile zu dinere `~/.bashrc` (oder das Äquivalänt uf dim Betriebsystem) hinzue.

    alias löli=git
