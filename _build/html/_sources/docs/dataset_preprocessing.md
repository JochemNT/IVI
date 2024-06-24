# Dataset en preprocessing

**Omschrijving datasets**

- Dataset 1: 

*Titel:* Vestigingen van bedrijven; bedrijfstak; gemeente (2022)  
*Link:* https://opendata.cbs.nl/statline/#/CBS/nl/dataset/81575NED/table?ts=1718732653537  
*Omschrijving:*  
Deze tabel bevat gegevens over het aantal vestigingen van bedrijven naar economische activiteit, gebaseerd op de Standaard Bedrijfsindeling 2008 (SBI 2008). De vestigingen zijn voorts ingedeeld naar de gemeentelijke indeling per 1 januari van het verslagjaar. De statistieken over het thema vestigingendemografie beschrijven de regionale verdeling van de populatie van bedrijfsvestigingen in Nederland. Met behulp van deze cijfers wordt onder andere inzichtelijk gemaakt waar bedrijven in Nederland zijn gevestigd en of bepaalde bedrijfstakken in bepaalde regio’s meer voorkomen dan in andere.
*Preprocessing:*  
Deze dataset is schoongemaakt door lege datapunten (de laatste twee) te verwijderen. Daarna zijn de datapunten en variabelen omgewisseld, zodat de variabelen overeenkomen met die van de andere datasets.

- Dataset 2:

*Titel:* Bevolking; hoogstbehaald onderwijsniveau en regio (2022)  
*Link:* https://opendata.cbs.nl/statline/#/CBS/nl/dataset/85525NED/table?ts=1718111990105  
*Omschrijving:*   
Deze tabel bevat cijfers over het hoogst behaalde onderwijsniveau van mensen van 15 tot 75 jaar die op 1 oktober van het verslagjaar in een Nederlandse gemeente stonden ingeschreven. In de tabel is de driedeling voor onderwijsniveau opgenomen en kunnen uitsplitsingen gemaakt worden naar regio. Het doel van het opleidingsniveaubestand is om voor een zo groot mogelijk deel van de Nederlanders het hoogste behaalde en hoogst gevolgde opleidingsniveau vast te leggen, zodat tal van onderzoeken kunnen worden uitgebreid met informatie over opleidingsniveau.
*Preprocessing:*  
Deze dataset is schoongemaakt door lege datapunten te verwijderen. Ook is de eerste kolom ('Bevolkingsaantal %') verwijderd en zijn de 5 categorieën van onderwijsniveau samengevoegd tot 3 categorieën: kolom 2 en 3 zijn samengevoegd en kolom 5 en 6 zijn samengevoegd.

- Dataset 3:

*Titel:* Inkomen van personen; persoonskenmerken, regio (2022)  
*Link:* https://opendata.cbs.nl/statline/#/CBS/nl/dataset/85712NED/table?ts=1718734295916  
*Omschrijving:*  
Deze tabel bevat gegevens over het inkomen van personen, uitgesplitst naar regio en diverse achtergrondkenmerken zoals geslacht, positie in het huishouden, leeftijd en sociaaleconomische categorie. De doelpopulatie omvat alle particuliere huishoudens met bekend inkomen. Peildatum voor de populatie is 1 januari van het verslagjaar, en peildatum voor de gemeentelijke indeling is 1 januari 2022. Het doel van deze dataset is om een beeld geven van de samenstelling en verdeling van het inkomen en vermogen van personen en huishoudens in Nederland.
*Preprocessing:*  
Deze dataset is schoongemaakt door lege datapunten te verwijderen. Daarna zijn alle variabelen behalve variabele 'Mediaan persoonlijk Inkomen' verwijderd uit de tabel.