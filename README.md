# Colonnine di ricarica in Provincia di Varese

In questo repository si trovano i dati relativi alle colonnine di ricarica attive in provincia di Varese. I dati sono aggiornati 20 aprile e sono stati estratti da OnData qui: https://github.com/ondata/rete_ricarica_veicoli_elettrici

I file che si trovano in questo repository sono:

-colonninevarese.py: il codice Python che legge il file di onData ed estrae i valori relativi alla sola provincia di Varese (vanno corretti i percorsi al file di onData, agli shapefile Istat di comuni e province che devono essere scaricati e i percorsi dei file di output)

-punti_ricarica_varese_con_comuni.csv: dataset con le coordinate delle colonnine e il nome del comune (alcuni esterni alla provincia di Varese)

-conteggio_colonnine_per_comune_varese: dataset con il conteggio delle colonnine per ogni comune (alcuni esterni alla provincia di Varese)

-PuntiRicaricaVarese.csv: dataset ripulito con le coordinate delle colonnine nei soli comuni della sola provincia di Varese

-ColonnineVarese: dataset ripulito con il conteggio delle colonnine della sola provincia di Varese
