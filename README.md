# rechnungspruefung-agent

Prototyp eines Rechnungsprüfungs-Agenten (Uni-Projekt).

## Ziel

Der Agent prüft eingehende Rechnungen automatisch, z. B. auf:

- Pflichtangaben nach § 14 UStG (Name/Anschrift, Steuernummer bzw. USt-IdNr., Rechnungsnummer, Datum, Leistungsbeschreibung, Netto, Steuersatz, Steuerbetrag)
- rechnerische Richtigkeit (Positionen, Summen, Umsatzsteuer)
- Abgleich mit Bestellung bzw. Lieferschein
- Dubletten (bereits erfasste Rechnungen)

## Projektstruktur

```
rechnungspruefung-agent/
├── src/                      # Quellcode des Agenten
├── data/
│   └── beispielrechnungen/   # Test- und Beispielrechnungen (keine echten Daten!)
├── docs/                     # Dokumentation, Konzept, Notizen
├── tests/                    # Tests
└── README.md
```

## Erste Schritte

```bash
git clone git@github.com:EneralBerlin/rechnungspruefung-agent.git
cd rechnungspruefung-agent
```

## Status

🚧 In Arbeit
