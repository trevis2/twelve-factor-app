12 factor app

metodo per creare SaaS
applicazioni stateless per piattaforme cloud

12 factor app riguarda:
la scalabilità
l'osservabilità (monitoraggio)
riproducibilità

---------------------
- setup del database
- versione di node
------------------
- codebase
il codebase deve essere versionato
1a1 fra applicazione e codice
1amolti fra codice e deploy

- dependencies
un manifest
separare codice dalle dipendenze
es. npm

- config
separare la configurazione dal codice e memorizzarle in variabili di ambiente

