# BandoCatcher

Motore gratuito per cercare finanziamenti, gare/appalti e concorsi, mantenendo sempre la fonte ufficiale.

## V1
- PWA statica, senza account e senza raccolta email
- ricerca e filtri per categoria, territorio, stato e fonte
- opportunità normalizzate con identificativo, scadenza, ultima verifica e link ufficiale specifico
- dataset reale di esempio da fonti ufficiali
- ingestion Python per TED, Funding & Tenders e inPA
- Source Registry separato tra fonti operative e fonti censite

## Principio
BandoCatcher organizza e rende ricercabile il dato; la fonte ufficiale resta il riferimento. Un record senza link ufficiale specifico non viene pubblicato come opportunità cliccabile.

## GitHub Pages
Il frontend è statico e vive nella root del repository. Il workflow di sincronizzazione aggiorna il dataset quando la pipeline viene eseguita.
