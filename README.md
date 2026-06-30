# GCVPC-GIS
Georeferenced Information System to be employ by Small Civil Protection Groups without big amount of resource
1.
Dashboard principale - 
Pagina home con panoramica delle squadre di protezione civile attive, 
stato operativo e accesso rapido alle funzionalità
2.
Gestione Squadre - Pagina per creare, modificare e visualizzare 
le squadre con: colore identificativo, nome personalizzato 
(Alfa, Bravo, Charlie, Delta, Echo, Romeo, ecc.), caposquadra, 
membri, radio assegnate, mezzi disponibili, luogo di destinazione, 
stato operativo (Operativa Turno 1/2/3, A Riposo, Di Scorta), 
locazione attuale e tipo di intervento. 
Da questa pagina si accede direttamente al log della squadra selezionata
3.
-Sistema Log Automatico con Export CSV - 
Pagina salvabile e richiamabile dalla principale che registra 
automaticamente un log con data/ora per ogni squadra e testo 
descrittivo per ogni azione. 
Ogni riga del log è editabile inline e cancellabile singolarmente. 
I dati vengono sempre salvati automaticamente in formato testo CSV 
(persistenza anche alla chiusura della pagina)
4.
Mappa Interattiva OpenStreetMap - Pagina con mappa centrata su 
Finale Emilia (44.8333° N, 11.2933° E) con layer personalizzabili: 
informazioni orografiche, canali, fiumi, distanze
5.
Segnalini Squadre sulla Mappa - Marker colorati per ogni squadra 
che aprono una scheda informativa con: 
composizione squadra, caposquadra, radio, mezzi assegnati, 
luogo di destinazione, percorso ottimale e tempo di arrivo stimato
6.
Routing e Calcolo Percorsi - Integrazione con servizio di routing 
per calcolare percorso ottimale e tempo di arrivo dalla posizione 
della squadra alla destinazione assegnata](https://michelemincone.com/installare-xampp-con-php-mysql-apache/

=================================================

1.
Dashboard principale - 
Pagina home con panoramica delle squadre di protezione civile attive, 
stato operativo e accesso rapido alle funzionalità
2.
Gestione Squadre - Pagina per creare, modificare e visualizzare 
le squadre con: colore identificativo, nome personalizzato 
(Alfa, Bravo, Charlie, Delta, Echo, Romeo, ecc.), caposquadra, 
membri, radio assegnate, mezzi disponibili, luogo di destinazione, 
stato operativo (Operativa Turno 1/2/3, A Riposo, Di Scorta), 
locazione attuale e tipo di intervento. 
Da questa pagina si accede direttamente al log della squadra selezionata
3.
-Sistema Log Automatico con Export CSV - 
Pagina salvabile e richiamabile dalla principale che registra 
automaticamente un log con data/ora per ogni squadra e testo 
descrittivo per ogni azione. 
Ogni riga del log è editabile inline e cancellabile singolarmente. 
I dati vengono sempre salvati automaticamente in formato testo CSV 
(persistenza anche alla chiusura della pagina)
4.
Mappa Interattiva OpenStreetMap - Pagina con mappa centrata su 
Finale Emilia (44.8333° N, 11.2933° E) con layer personalizzabili: 
informazioni orografiche, canali, fiumi, distanze
5.
Segnalini Squadre sulla Mappa - Marker colorati per ogni squadra 
che aprono una scheda informativa con: 
composizione squadra, caposquadra, radio, mezzi assegnati, 
luogo di destinazione, percorso ottimale e tempo di arrivo stimato
6.
Routing e Calcolo Percorsi - Integrazione con servizio di routing 
per calcolare percorso ottimale e tempo di arrivo dalla posizione 
della squadra alla destinazione assegnata
------------------------------------------------------------------------
________________________________________
Manuale dello Sviluppatore
________________________________________
Scopo del progetto
________________________________________
PC-GIS è una piattaforma GIS completamente offline progettata 
per supportare le attività operative della Protezione Civile comunale 
durante emergenze idrauliche, idrogeologiche e di Protezione Civile.
Il sistema deve funzionare senza connessione Internet e consentire la 
gestione delle squadre operative, 
della cartografia, 
dei layer informativi, 
dei report squadra e 
del monitoraggio del territorio.
________________________________________
Obiettivi
•	funzionamento completamente offline
•	multipiattaforma
•	codice modulare
•	cartografia locale
•	database locale
•	semplicità di utilizzo
•	elevate prestazioni
Tecnologie
HTML5
CSS3
JavaScript ES2023
Leaflet Offline
GeoJSON
IndexedDB
LocalStorage
MBTiles
________________________________________
Architettura
Interfaccia Utente
↓
Controller
↓
Motore GIS
↓
Database Locale
↓
Layer Cartografici
________________________________________
Moduli software
Dashboard
Gestione Squadre
Gestione Operatori
Gestione Mezzi
Mappa GIS
Layer Manager
GPS
Report
Criticità
Ricerca
Esportazione
Backup
Impostazioni

Database
Il database locale in formato di cartelle e sotto cartelle conterrà:
Squadre
Operatori
Mezzi
Report
Eventi
Criticità
Fotografie
Waypoint
Layer
Configurazione
________________________________________
Layer GIS previsti
Confini Comunali
Viabilità
Edifici Strategici
Ponti
Argini
Canali
Fiumi
Destra Idraulica
Sinistra Idraulica
Stanti
Progressive Chilometriche
Aree Allagabili
Frane
Idrovore
Chiaviche
COC
Aree di Attesa
Aree di Ricovero
Aree di Ammassamento
Idranti
Punti Acqua
________________________________________
Compatibilità
Windows
Linux
macOS
Android
iPad-OS
iOS
________________________________________
Requisiti
Nessuna connessione Internet
Nessuna dipendenza da CDN
Nessun server
Installazione mediante semplice copia della cartella, funzionante anche mediante chiavetta USB
________________________________________
Convenzioni del codice
Ogni funzione documentata.
Ogni modulo indipendente.
Nessun codice duplicato.
Commenti esaustivi.
Naming uniforme.
________________________________________
Gestione versioni
Versione 6.0 (a partire da una idea precedente : Gestione Squadre 5.1 © 2026 Tutti i diritti riservati • Sviluppato da Alex IU4QQD)
Versione 6.5
Versione 7.0
Versione 8.0


)
