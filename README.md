# magic-link-tester-installer

You can download the latest clickonce version here
https://raw.githubusercontent.com/Microarea/magic-link-tester-installer/gh-pages/Installer/setup.exe

Magic Link Tester   
La piattaforma Magiclink offre un metodo efficiente per accedere e sfruttare le risorse ERP attraverso l'uso di Web Services. I Web Services sono componenti di logica di programma accessibili tramite Internet o una connessione HTTP. Ciò significa che i fornitori di informazioni possono interagire tra loro senza preoccuparsi dei dettagli tecnici sottostanti, sia sul front-end che sul back-end.
 
In sostanza, i Web Services fungono da interfacce standardizzate che consentono a diverse applicazioni e sistemi di comunicare e scambiarsi dati in modo sicuro e affidabile. Questi pezzi di logica del programma, espressi sotto forma di oggetti, sono accessibili da qualsiasi client che supporti il protocollo HTTP.
 
Un aspetto importante dei Web Services è la possibilità di utilizzare il formato XML standard per lo scambio di dati. Questo offre un alto livello di flessibilità e interoperabilità, poiché XML è comprensibile per molti linguaggi di programmazione e piattaforme.
 
Grazie all'architettura basata su Web Services della piattaforma magiclink, gli utenti possono facilmente prelevare i dati necessari e utilizzarli secondo le proprie esigenze, senza dover conoscere i dettagli tecnici interni del sistema ERP sottostante. Questo contribuisce a semplificare e ottimizzare l'integrazione di diverse soluzioni e applicazioni aziendali, rendendo la piattaforma magiclink una scelta potente e conveniente per gli utenti che cercano di ottimizzare i loro flussi di lavoro aziendali.

Fondamentalmente è suddiviso in 3 sezioni:
1. Barra degli strumenti principale:
Dove puoi gestire le varie opzioni di Magic Link Tester, gestire e accedere a TbLoader, modificare i parametri dell'applicazione come data e timeout e quindi gestire l'aspetto del carattere e l'impostazione del colore di sfondo.
2. Esplora documenti:
Dove è possibile selezionare il report o il documento da utilizzare con Magic Link.
3. Pagine delle schede:
Dove puoi eseguire azioni come GetData, SetData, ecc., tramite Web Services con Magic Link.

![image](https://github.com/Microarea/magic-link-tester-installer/assets/116000736/23d5644c-687a-4424-82ff-ecda29875e55)

Eseguire un GetData
Per eseguire correttamente un'operazione GetData, segui questi passaggi:
1. Seleziona le informazioni necessarie per estrarre il documento desiderato dal sistema, come Application, Module, Document/Report e Profile.
2. Vai su "Get Data" e trova il pulsante "Return parameters for find" nell'interfaccia. Cliccandolo, il Magic Link Tester recupererà l'XML relativo al documento corrente.
3. Una volta visualizzato l'XML, assicurati di esaminarlo attentamente. Verifica che contenga tutte le informazioni necessarie per l'estrazione corretta del documento desiderato.
4. Rimuovi eventuali campi vuoti dall'XML. I campi vuoti potrebbero causare errori nella query di estrazione, quindi è importante assicurarsi che siano completati correttamente o eliminati se non necessari. . ( come indicato nel riquadro arancione ).
5. Dopo aver verificato e modificato l'XML se necessario, il sistema sarà pronto per eseguire l'operazione GetData. Premi il pulsante "Ottieni dati" per avviare il processo di estrazione.

![image](https://github.com/Microarea/magic-link-tester-installer/assets/116000736/bef0e9e3-c770-441b-8d65-9f1b26e4fb5b)


Il risultato di GetData sarà mostrato nella sezione destra della sezione Get Data (una scheda per ogni documento estratto), e sarà mostrato anche nella sezione Log.


![image](https://github.com/Microarea/magic-link-tester-installer/assets/116000736/4994a31d-4c16-4548-b6ca-de3d9a8571f3)


Eseguire un SetData
• Copiare il documento selezionato nella scheda "SetData".
Nella sezione SetData, proprio come nella scheda GetData, il lato sinistro viene utilizzato per inserire l'xml che verrà inviato a Mago, e il lato destro mostra l'output della chiamata al servizio web.
![image](https://github.com/Microarea/magic-link-tester-installer/assets/116000736/22936383-ae11-4ca0-ad4f-e743a301a8be)


Eseguire un TbWebMethod
Sono state inserite queste due funzionalità d’esempio. Inserendo i dato richiesti è possibile ottenere il risulttao desiderato.
![image](https://github.com/Microarea/magic-link-tester-installer/assets/116000736/698dc7c1-7dd9-4d81-b809-28b1e8e0fa97)






