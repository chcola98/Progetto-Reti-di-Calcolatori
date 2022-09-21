Reti di calcolatori

# Work in progress #
Progetto svolto per il corso di Reti di Calcolatori 2021/2022
Chiara Colaizzi (matricola 1795759)

# Scopo del progetto #

work in progress


# Architettura di riferimento e tecnologie usate (con un diagramma)
![client (1)](https://user-images.githubusercontent.com/49658009/176608526-d68aaf32-e7db-40bf-bb35-c78723df2438.png)

# Indicazioni sul soddisfacimento dei requisiti

Requisiti di progetto e Tecnologie utilizzate
1. Il servizio REST che implementate (SERV) deve offrire a terze parti delle API documentate.
    * **Apidoc**: utilizzato per fornire la documentazione delle API utilizzate;
2.	SERV si deve interfacciare con almeno due servizi REST di terze parti,
3.	Almeno uno dei servizi REST esterni deve essere “commerciale”,
4.	Almeno uno dei servizi REST esterni deve richiedere oauth:

    * **API-FOOTBALL**: utilizzata per mostrare risultati, statistiche e classifiche in tempo reale.
    *	ScoreBat API: utilizzata per mostrare gli highlights e i goal ufficiali di ogni partita della competizione.
    *	**Google Calendar**: utilizzato per creare/aggiungere eventi al proprio calendario (tramite accesso Oauth).
    *	**Google**: utilizzato per l’accesso al sito web tramite protocollo Oauth.

5.	La soluzione deve prevedere l'uso di protocolli asincroni:
    * **RabbitMQ**

6.	Il progetto deve prevedere l'uso di Docker e l'automazione del processo di lancio, configurazione e test:
    * **Docker**: utilizzato per la creazione della Web App su più container.

7.	Il progetto deve essere su GIT (GITHUB, GITLAB ...) e documentato con un README: 
    *	**GitHub**: utilizzato per condividere i file e permettere al gruppo di lavorare allo stesso progetto contemporaneamente;
    * **README.md**: utilizzato per 

8.	Deve essere implementata una forma di CI/CD:
    * **GitHub Actions**: è stata implementata una forma di CI/CD ed far partire i test quando viene effettuata una push;

9.	Requisiti minimi di sicurezza devono essere considerati e documentati:

# istruzioni per l'installazione
...

# istruzioni per il test
...

# Documentazione delle API
...
