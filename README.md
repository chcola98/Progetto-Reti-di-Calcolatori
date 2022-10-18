Reti di calcolatori

# LiveAbroad #
Progetto svolto per il corso di Reti di Calcolatori 2021/2022
Chiara Colaizzi (matricola 1795759)

# Scopo del progetto #

**LiveAbroad** è una WebApp pensata per aiutare chiunque decida di andare a vivere all’estero o lontano dalla propria città.
Attraverso l’utilizzo di diverse API consente all’utente di cercare informazioni sui documenti richiesti e sul costo della vita nel Paese prescelto.
Effettuando l'accesso alla WebApp, sarà possibile ricevere via mail un resoconto delle ricerche effettuate in formato PDF. Inoltre, effettuando l'accesso con il proprio account Google sarà possibile salvare il resoconto ottenuto sul proprio Google Drive così da averlo a disposizione in qualsiasi momento.

# Architettura di riferimento e tecnologie usate (con un diagramma)
![VISA_LIST](https://user-images.githubusercontent.com/49658009/196391073-7fb6ca1d-ec6a-4da4-81ee-19f4b2e1e36c.jpg)

# Indicazioni sul soddisfacimento dei requisiti

Requisiti di progetto e Tecnologie utilizzate

1. Il servizio REST che implementate (SERV) deve offrire a terze parti delle API documentate.
![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)
   * **Apidoc**: utilizzato per fornire la documentazione delle API utilizzate; 

   
2.	SERV si deve interfacciare con almeno due servizi REST di terze parti;
![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)


3.	Almeno uno dei servizi REST esterni deve essere “commerciale”;
![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)

4.	Almeno uno dei servizi REST esterni deve richiedere oauth:
![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)

   
    * **Visa List**: per avere informazioni riguardanti Visti e documenti richiesti nel Paese prescelto;
    * **Cost of living Prices by City & Country** : per avere informazioni riguardanti il costo della vita nella città o nel Paese prescelto;
    * **Google Drive**: per salvare sul proprio Drive il riepilogo dei dati ottenuti nella ricerca.

5.	La soluzione deve prevedere l'uso di protocolli asincroni:
![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)
   
    * **RabbitMQ**: utilizzato per gestire l'invio delle mail di riepilogo attraverso l'uso di **Nodemailer**.

6.	Il progetto deve prevedere l'uso di Docker e l'automazione del processo di lancio, configurazione e test:
![icons8-ok-32](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)
   
    * **Docker**: utilizzato per la creazione della WebApp su più container.

7.	Il progetto deve essere su GIT (GITHUB, GITLAB ...) e documentato con un README:
![icons8-ok-16](https://user-images.githubusercontent.com/49658009/195682878-d59bfc7a-c42d-42a3-8ee6-11d1c5d6e435.png)
    
      *	**GitHub**: utilizzato per condividere i file;
      * **README.md**: utilizzato per illustrare il progetto;

8.	Deve essere implementata una forma di CI/CD:
    
      * **GitHub Actions**: è stata implementata una forma di CI/CD ed far partire i test quando viene effettuata una push;

9.	Requisiti minimi di sicurezza devono essere considerati e documentati:


------
# istruzioni per l'installazione
...

# istruzioni per il test
...

# Documentazione delle API
...
