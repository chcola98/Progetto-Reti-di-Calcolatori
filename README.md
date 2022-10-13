Reti di calcolatori

# LiveAbroad #
Progetto svolto per il corso di Reti di Calcolatori 2021/2022
Chiara Colaizzi (matricola 1795759)

# Scopo del progetto #

**LiveAbroad** è una WebApp pensata per aiutare chiunque decida di andare a vivere all’estero o lontano dalla propria città.
Attraverso l’utilizzo di diverse API consente all’utente di cercare informazioni sui documenti richiesti per vivere nel Paese prescelto, di cercare informazioni sul costo della vita e di cercare un alloggio nel luogo indicato.


# Architettura di riferimento e tecnologie usate (con un diagramma)
![VISA LIST_page-0001](https://user-images.githubusercontent.com/49658009/195655355-8836e0c2-3bee-4322-adf5-ae0ba3e6e570.jpg)

# Indicazioni sul soddisfacimento dei requisiti

Requisiti di progetto e Tecnologie utilizzate

1. Il servizio REST che implementate (SERV) deve offrire a terze parti delle API documentate.\*         \*![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)
   * **Apidoc**: utilizzato per fornire la documentazione delle API utilizzate; 

   
2.	SERV si deve interfacciare con almeno due servizi REST di terze parti;![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)


3.	Almeno uno dei servizi REST esterni deve essere “commerciale”;  ![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)

4.	Almeno uno dei servizi REST esterni deve richiedere oauth:  ![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)

   
    * **Visa List**: per avere informazioni riguardanti Visti e documenti richiesti nel Paese prescelto;
    * **Cost of living Prices by City & Country** : per avere informazioni riguardanti il costo della vita nella città o nel Paese prescelto;
    * **Airbnb**: per consentire la ricerca di una casa in affitto nella città o nel Paese prescelto.
    * **Gmail**: per ricevere una mail di riepilogo dei dati ottenuti nella ricerca.

5.	La soluzione deve prevedere l'uso di protocolli asincroni:  ![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)
   
    * **RabbitMQ**: utilizzato per gestire l'invio delle mail di riepilogo attraverso l'uso di **Nodemailer**.

6.	Il progetto deve prevedere l'uso di Docker e l'automazione del processo di lancio, configurazione e test: ![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)
   
    * **Docker**: utilizzato per la creazione della Web App su più container.

7.	Il progetto deve essere su GIT (GITHUB, GITLAB ...) e documentato con un README:  ![icons8-ok-16](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)
    
      *	**GitHub**: utilizzato per condividere i file;
      * **README.md**

8.	Deve essere implementata una forma di CI/CD:  ![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)
    
      * **GitHub Actions**: è stata implementata una forma di CI/CD ed far partire i test quando viene effettuata una push;

9.	Requisiti minimi di sicurezza devono essere considerati e documentati:  ![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)

# istruzioni per l'installazione
...

# istruzioni per il test
...

# Documentazione delle API
...
