
# Dati Ufficiali da AMAT Spa - Palermo


Qesto è il repository dove vengono conservati i dati ufficiali prodotti da AMAT e pubblicati sul sito del comune di Palermo alla sezione Open Data.
I dati sono pubblicati in formato GFTS

## Versioni

Qui è possibile accedere alle vecchie versioni del dataset [https://github.com/openamat/Official-Data/releases](https://github.com/openamat/Official-Data/releases)
 
## Fomato GFTS
**General Transit Feed Specification (GTFS)**, conosciuto come GTFS statico per differenziarlo dal GTFS in realtime, definisce un formato per la schedulazione degli orari del trasporto pubblico e associare informazioni sulla geolocalizzazione.

Ovviamente sono dati leggibili da un software GIS

La specifica GTFS (General Transit Feed Specification) è stata sviluppata da Google e definisce un formato per rappresentare informazioni orarie di un sistema di trasporti (bus, metro, treno, etc) associandole ad informazioni geografiche.

La specifica struttura i dati organizzandoli in un insieme di file CSV.

I più importanti sono i seguenti:

agency – informazioni dell’azienda che gestisce i trasporti;
routes – informazioni su linee;
trips – informazioni su corse per  linea;
stops – fermate geolocalizzate;
stop_times – orario di arrivo e partenza e sequenza per ogni corsa in ciascuna fermata;
calendar – periodo di servizio trasporti su base settimanale;
calendar_dates – date in cui vi sono delle eccezioni rispetto a quanto descritto in calendar (ad. es. feste)
Per la specifica completa si rimanda alla pagina ufficiale GTFS [Specifiche GTFS](https://developers.google.com/transit/gtfs/reference)
