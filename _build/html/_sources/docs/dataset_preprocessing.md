# Dataset en preprocessing

Nadat we ons onderwerp hebben gekozen gingen we ieder opzoek naar relevante datasets. Omdat we vaak uitkwamen op datasets van het [Centraal Bureau van de Statistiek (CBS)](https://www.cbs.nl/nl-nl/dossier/nederland-regionaal/provincies), hebben we besloten om al onze datasets van deze website te halen.

## Schoonmaken van de datasets

De website van het CBS heeft bij elke dataset de optie om bepaalde datapunten en variabelen te selecteren, waardoor irrelevante data weggelaten wordt. Bij het downloaden van de datasets blijft de irrelevante data achterwege, wat ons wat *preprocesing* heeft gescheeld. Als er dan toch overbodige kolommen of rijen gedownload waren, hebben we die met behulp van Python en de Pandas *library* verwijderd. Op dezelfde manier hebben we incomplete datapunten (rijen waar bepaalde waardes ontbreken) verwijderd uit de datasets. Op deze manier hielden we enkel complete en goed bruikbare datasets over.

## Beschrijving van de variabelen

Gebruikte datasets met bijbehorende variabelen:

| Dataset                            | Variabele(n)                              |
|------------------------------------|-------------------------------------------|
| Persoonlijk inkomen per provincie  | • Mediaan inkomen                         |
| Onderwijsniveau per provincie      | • Laag onderwijsniveau (%)<br>• Middelbaar onderwijsniveau (%)<br>• Hoog onderwijsniveau (%)  |
| Soorten bedrijven per provincie    | • Industrie<br>• Landbouw<br>• Horeca<br>• Totaal bedrijven  |
| Misdaden per provincie             | • Verdachten per 10.000 inwoners          |
| Groenvoorzieningen per gemeente    | • Totaal bos en open natuurlijk terrein (ha) |
| Status huwelijk per provincie      | • Gehuwd (%)<br>• Gescheiden (%)          |
| Woontevredenheid per provincie     | • 2009<br>• 2012<br>• 2015<br>• 2018<br>• 2021 |


| Soort variabele     | Bijbehorende variabele(n)                         |
|---------------------|--------------------------------------------------|
| Continuous / Ratio  | • Mediaan inkomen<br>• Laag onderwijsniveau (%)<br>• Middelbaar onderwijsniveau (%)<br>• Hoog onderwijsniveau (%)<br>• Totaal bos en open natuurlijk terrein (ha)<br>• Gehuwd (%)<br>• Gescheiden (%)<br>• 2009<br>• 2012<br>• 2015<br>• 2018<br>• 2021 |
| Discrete / Ordinal  | • Industrie<br>• Landbouw<br>• Horeca<br>• Totaal bedrijven |
| Discrete / Ratio    | • Verdachten per 10.000 inwoners                 |
