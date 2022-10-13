Reti di calcolatori

# LiveAbroad #
Progetto svolto per il corso di Reti di Calcolatori 2021/2022
Chiara Colaizzi (matricola 1795759)

# Scopo del progetto #

**LiveAbroad** è una WebApp pensata per aiutare chiunque decida di andare a vivere all’estero o lontano dalla propria città.
Attraverso l’utilizzo di diverse API consente all’utente di cercare informazioni sui documenti richiesti per vivere nel Paese prescelto, di cercare informazioni sul costo della vita e infine consente di cercare un alloggio nel luogo indicato.
Inoltre, effettuando l’accesso con il proprio account Google, è possibile creare un documento di riepilogo con le informazioni trovate e riceverlo direttamente sulla propria casella di posta Gmail.


# Architettura di riferimento e tecnologie usate (con un diagramma)
![VISA LIST_page-0001](https://user-images.githubusercontent.com/49658009/195655355-8836e0c2-3bee-4322-adf5-ae0ba3e6e570.jpg)

# Indicazioni sul soddisfacimento dei requisiti

Requisiti di progetto e Tecnologie utilizzate
1.[x] Il servizio REST che implementate (SERV) deve offrire a terze parti delle API documentate. [x]
    * **Apidoc**: utilizzato per fornire la documentazione delle API utilizzate;
2.	SERV si deve interfacciare con almeno due servizi REST di terze parti; [x]
3.	Almeno uno dei servizi REST esterni deve essere “commerciale”; [x]
4.	Almeno uno dei servizi REST esterni deve richiedere oauth: [x]

    * **Visa List**: per avere informazioni riguardanti Visti e documenti richiesti nel Paese prescelto;
    *	**Cost of living Prices by City & Country** : per avere informazioni riguardanti il costo della vita nella città o nel Paese prescelto;
    *	**Airbnb**: per consentire la ricerca di una casa in affitto nella città o nel Paese prescelto.
    *	**Gmail**: per ricevere una mail di riepilogo dei dati ottenuti nella ricerca.

5.	La soluzione deve prevedere l'uso di protocolli asincroni: [x]
    * **RabbitMQ**: utilizzato per gestire l'invio delle mail di riepilogo attraverso l'uso di **Nodemailer**.

6.	Il progetto deve prevedere l'uso di Docker e l'automazione del processo di lancio, configurazione e test: [x]
    * **Docker**: utilizzato per la creazione della Web App su più container.

7.	Il progetto deve essere su GIT (GITHUB, GITLAB ...) e documentato con un README: [x]
    *	**GitHub**: utilizzato per condividere i file;
    * **README.md**

8.	Deve essere implementata una forma di CI/CD:
    * **GitHub Actions**: è stata implementata una forma di CI/CD ed far partire i test quando viene effettuata una push;

9.	Requisiti minimi di sicurezza devono essere considerati e documentati:

# istruzioni per l'installazione
...

# istruzioni per il test
...

# Documentazione delle API
...
