---
title: "Hello World"
date: 2019-08-09T13:31:00+02:00
draft: false
---
# Hallo Welt!

Ich, Stefan von <a href="stousn.at">stousn.at</a>, habe mich dazu entschieden diesen kleinen Blog zu erstellen.
In dem ersten Post möchte ich euch kurz erzählen warum ihr hier was und wie lesen/sehen werdet.

<!--more-->

## Warum
Früher hatte ich schon den einen oder anderen Blog. Aus zeitlichen Gründen habe ich diese aber neben dem Studium und der Arbeit nicht weiter betrieben. 
Nun bin ich mit meinem Studium aber bald fertig (Ich sollte auch gerade an der Masterarbeit schreiben \**hust*\*) und wollte wieder einfach einen kleinen Blog. 
Twitter (<a href="http://twitter.com/5tousn">@5tousn</a>) ist da oft nicht der richtige Ort dazu und auch meine <a href="https://stousn.at">Homepage</a> ist nicht passend. Also habe ich mich für einen Blog entschieden, den ich per Redirect der Subdomain blog.stousn.at "vermarkte".

## Inhalt
Grenzen, was den Inhalt oder den zeitlichen Rahmen angeht, setze ich mir hier nicht. Nur so viel: Ich werde eventuell über das eine oder andere Projekt schreiben aber auch über Ausflüge die ich mit Bildern dokumentiere. Außerdem bekommen die YouTube Videos auf dem Kanal von Vanessa (<a href="http://twitter.com/Kroko615">@Kroko615</a>) und mir auch jeweils einen eigenen Beitrag. 

## Technologie
Dass der nächste Blog nicht auf Wordpress, Blogger oder Co gehostet wird, war für mich von Anfang an klar. Ich wollte selbst verantwortlich dafür sein wie und wo der Blog betrieben wird. 

Markdown ist eine Auszeichnungssprache, die man von den GitHub ReadMe-Files kennt. Ich verwende es für alle mögliche Art von Text und Dokumentation und mit einem Projekt namens Marp sogar für Präsentationen. Also dachte ich mir, es muss doch auch einen Markdown rendering Mechanismus geben, der mir HTML ausspuckt. 
Nun ja, den gibt es, aber besser noch, mit Hugo (das Go im Namen steht für die Programmiersprache) kann man sich gleich ganze statische Websites generieren lassen.

Aufgesetzt war das Ganze in gut einer Stunde inkl.

* GitHub Repos anlegen,
* Hugo Projekt anlegen,
* Template installieren,
* Impressum einfügen,
* Seite hosten und
* DNS Einträge schreiben.
  
Gehostet wird der Blog auf GitHub Pages. Ein kleines Bash-Skript baut mir die Seite mit Hugo und deployed (also git pusht) sie mir gleich.

Und nun fehlt nur mehr der Inhalt, der in Markdown geschrieben wird. Das ~~muss~~ kann ich auch in Zukunft selbst machen.
