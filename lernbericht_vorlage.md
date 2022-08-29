# Lern-Bericht
Hugo Duarte Novas

## Einleitung

Bei dem Modul 133 geht es darum mit JSF Web Applikationen mit Sessions zu entwickeln. Bei diesem Auftrag sollten wir Bilder einfügen sodass man sein Charakter von Pokemon GO personalisieren kann.

## Was habe ich gelernt?

Ich habe gelernt, wie man Bilder einfügt in .xhtml Dateien mit der Hilfe von JSF.

## Beschreibung

```java
<!-- Hier kreiere ich einen CommandLink. Wenn dieser aktiviert wird, geht man zu einer neuen Seite. -->
<h:commandLink value="" action="helle_haut.xhtml">
<!-- Hier rufe ich den Setter auf -->
                <f:setPropertyActionListener target="#{helloManagedBean.favourite}" value="links"/>
<!-- Hier füge ich das Bild hinzu, der CommandLink wird beendet -->
                <h:graphicImage value="9954_PokemonBilder/9954_PokemonBilder/h.png" width="200"/>
            </h:commandLink>
```

Hier kann man sehen einen Teil meines Programmes. Ich habe hier zwei Bilder hinzugefügt, welche dann zu jeweils unterschiedliche .xhtml Seiten führen.
* Ein deutliches, aussagekräftiges Bild oder eine kommentierte Bildschirm-Aufnahme
* Ein gut dokumentierter Code-Fetzen
* Ein Link zu einem *selbst aufgenommenen* youtube-Video oder `.gif`.

## Verifikation

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflektion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
