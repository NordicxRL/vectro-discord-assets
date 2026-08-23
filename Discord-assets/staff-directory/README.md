# Staff Directory – getrennte Bereiche

Der Staff-Bereich ist in drei unabhängige GitHub-Ordner aufgeteilt:

```text
staff-directory/
├── founder/
│   ├── founder-and-leadership.png
│   └── cards/
├── rocket-league-management/
│   ├── rocket-league-management.png
│   └── cards/
└── general-management/
    ├── general-management.png
    └── cards/
```

In jedem Bereich liegt ein fertig angeordnetes Board und zusätzlich ein Unterordner mit den einzelnen Karten. So kann später genau der betroffene Bereich ausgetauscht werden.

Jedes Board verwendet maximal drei vergrößerte Karten pro Reihe. Bleiben danach eine oder zwei Karten übrig, ist die letzte Reihe mittig ausgerichtet. Die Anordnung ist fest in das PNG gerendert und wird von Discord nicht verändert.

Alle Personenbilder sind neutrale Rückenansichten mit Vectro-Kleidung. Das frühere Kartenlogo oben rechts, die Nummern, die Kategoriezeile und der Hinweis am unteren Boardrand wurden entfernt. Die Namen und Aufgaben unter `general-management` sind Platzhalter.

Die zugehörigen Webhook-Dateien liegen außerhalb des GitHub-Bildordners unter:

- `webhook/components-v2/staff/`
- `webhook/discohook/staff/`

Jeder Bereich wird als eigene Discord-Nachricht gesendet. Alle drei Nachrichten können denselben Webhook `VECTRO STAFF` verwenden.
