# Woningdashboards

Zelfstandige HTML-dashboards voor woonlocaties van Ipse de Bruggen.
Elk dashboard is één bestand zonder server: openen in de browser is genoeg.

| Woning | Map |
|---|---|
| Van Beverninkstraat 1A | `beverninkstraat-1a/` |
| Rottumeroog (Nootdorp) | `rottumeroog/` |

## Uitgangspunten

- **Geen tweede dossier.** Er staan geen cliëntgegevens in. Het cliëntplan, het
  signaleringsplan en het medisch protocol blijven leidend.
- **Per apparaat.** Wat iemand aanvinkt of invult blijft in de browser van dat
  apparaat (localStorage) en gaat niet naar een server. Elke woning heeft een
  eigen opslagsleutel, dus de dashboards komen elkaar niet in de weg.
- **Niet vindbaar.** Alle pagina's staan op `noindex`, zodat zoekmachines ze
  niet opnemen. De link zelf is wel voor iedereen te openen.

## Een woning toevoegen

Maak een map met de naam van de woning, zet het dashboard erin als
`index.html` en voeg een kaart toe aan de `index.html` in de hoofdmap.
