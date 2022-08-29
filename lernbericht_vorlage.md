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

![Unbenannt](https://user-images.githubusercontent.com/106603796/187195114-1c0c16b8-8a71-42f8-a6a6-95926023dc7e.PNG)

## Verifikation

Bei dem Bild kann man deutlich sehen, dass zwei Bilder sichtbar sind. Somit ist klar, dass ich die Aufgabe abgeschlossen habe.

# Reflektion zum Arbeitsprozess

Gut lief das Recherchieren der Informationen zum Umsetzen des Programmes.

Was nicht so gut lief war leider das Organisieren. Ich habe diese Aufgabe unterschätzt und den Lehrer missverstanden.

**VBV**: Ich soll besser zuhören und die Aufgaben ganz durchlesen, damit ich besser vorwärts komme.
