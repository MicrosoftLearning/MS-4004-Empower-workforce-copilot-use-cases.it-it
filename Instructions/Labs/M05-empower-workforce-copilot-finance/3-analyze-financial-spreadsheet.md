#  Analizzare un foglio di calcolo finanziario usando Microsoft 365 Copilot in Excel
---
Per i professionisti del settore finanziario, Microsoft 365 Copilot in Excel offre numerosi vantaggi, come la possibilità di porre domande sul set di dati in linguaggio naturale anziché solo le formule. Lo strumento può rivelare correlazioni, suggerire scenari di simulazione e creare visualizzazioni avanzate in base alle query. Ad esempio, è possibile usare Microsoft 365 Copilot in Excel per suddividere i dati di vendita per tipo e canale. In alternativa, è possibile proiettare l'impatto di una modifica delle variabili nei dati e quindi generare un grafico per visualizzarlo. È anche possibile modellare il modo in cui una modifica al tasso di crescita per una variabile influisce sul margine lordo.

In conclusione, automatizzando le attività ripetitive, Microsoft 365 Copilot in Excel sblocca approcci più creativi e innovativi all'interno della forza lavoro, accelerando i progressi in varie linee di business. È uno strumento prezioso per i professionisti del settore finanziario che vogliono semplificare i processi quotidiani e prendere decisioni più informate.

Quando si usa Microsoft 365 Copilot in Excel, è necessario disporre di una tabella di Excel che include dati in un foglio di lavoro. È possibile trasformare rapidamente un intervallo di celle in una tabella di Excel seguendo questa procedura:

1.  Selezionare la cella o l'intervallo nei dati.
2.  Selezionare il formato **Home&gt; come tabella**.
3.  Nella finestra di dialogo **Formato come tabella** selezionare la casella di controllo accanto a **Tabella personale con intestazioni** se si desidera che la prima riga dell'intervallo sia la riga di intestazione.
4.  Seleziona **OK**.

In questo esercizio si userà Microsoft 365 Copilot in Excel per analizzare un foglio di calcolo con le tendenze di mercato già presente in una tabella di Excel. Questo esercizio esamina molte delle funzioni predefinite e delle richieste di Copilot.

### Esercizio

In qualità di Direttore di marketing di Fabrikam, si vuole analizzare l'efficacia delle campagne di marketing Q1 dell'azienda. Il direttore di marketing ti ha fornito un foglio di calcolo che identifica ogni campagna di marketing che l'azienda ha intrapreso durante il primo trimestre. Il foglio di calcolo fornisce cifre di base sul budget e sui ricavi e il numero di utenti mirati e coinvolti. Ora è il tuo compito di analizzare i numeri per determinare l'efficacia di ogni tipo di campagna.

Seguire questa procedura per usare Microsoft 365 Copilot in Excel per analizzare i dati visualizzati nel foglio di calcolo delle campagne di marketing Q1:

1.  Selezionare il collegamento seguente per scaricare il foglio di calcolo delle [campagne di marketing di Fabrikam Q1](https://go.microsoft.com/fwlink/?linkid=2269124).
2.  Al termine del download, spostare il file nell'account OneDrive e quindi aprire e chiudere il file per ottenerlo nell'elenco dei file usati più di recente .
3.  Se nel browser Microsoft Edge è aperta una scheda di Microsoft 365, selezionarla ora; in caso contrario, aprire una nuova scheda e immettere l'URL seguente: **https://www.office.com**
4.  Nella home page di **Microsoft 365**, selezionare l'icona di **Excel** nel pannello di navigazione a sinistra.
5.  In **Excel**, nella pagina **File**, selezionare **Campagne di marketing di Fabrikam Q1 **dall'elenco di file.
6.  Selezionare l'opzione **Copilot** sul lato destro della barra multifunzione.
7.  Nel riquadro **Copilot** visualizzato, prendere nota delle richieste predefinite visualizzate sopra il campo delle richieste. Prima di selezionare una di queste richieste predefinite per migliorare l'analisi, è prima necessario che Copilot apporti alcune modifiche specifiche al foglio di calcolo. Per iniziare, si vuole che Copilot identifichi i tipi di campagna più redditizi. A tale scopo, utilizzare la richiesta seguente:
    
    **Creare una tabella pivot per analizzare i ricavi totali generati da ogni tipo di campagna**.
8.  Esaminare i risultati di questa richiesta. Copilot ha mostrato due finestre di risposta. La prima risposta includeva una tabella pivot che riepilogava i ricavi totali per tipo di campagna. La seconda risposta includeva una spiegazione di ciò che ha fatto nella prima risposta. Nella prima risposta contenente questa tabella, selezionare il pulsante **+Aggiungi a un nuovo foglio**. In questo modo, questa tabella viene aggiunta al **foglio 2** di questo foglio di calcolo, che Copilot ha quindi aperto automaticamente.
9.  Osservando il **foglio 2**, si noterà che Copilot non ha creato un grafico per accompagnare la tabella pivot. Esaminando la richiesta inviata, ci si rende conto che è stato appena chiesto di creare una tabella pivot. Non si è mai parlato di un grafico. Si vuole visualizzare una visualizzazione di questi dati, quindi si vuole immettere una richiesta che chiede a Copilot di generare un grafico per procedere con la tabella pivot nel **foglio 2**. Notare tuttavia che, mentre si è nel **foglio 2**, il campo di richiesta è disabilitato.
    
    > **NOTA:** il campo di richiesta è abilitato solo nel foglio con la tabella di Excel. Per questo foglio di calcolo, questo è **foglio 1**. Man mano che si continua con questo esercizio, ogni volta che Copilot aggiunge dati a un nuovo foglio, è necessario tornare al **foglio 1** per richiedere altre modifiche.
10. Selezionare **foglio 1** e quindi immettere la richiesta seguente:
    
    **Nel foglio 2 è stata creata una tabella pivot per analizzare i ricavi totali generati da ogni tipo di campagna. Creare un grafico nel foglio 2 per visualizzare questi dati**.
11. Esaminare i risultati. Se Copilot ha creato un grafico che mostra i ricavi per tipo di campagna, procedere con il passaggio successivo. Tuttavia, se Copilot ha visualizzato un messaggio che indica che non è possibile lavorare su un foglio diverso da quello originale che contiene la tabella di Excel, è necessario semplificare la richiesta precedente. In questo caso, inserire la seguente richiesta:
    
    **Calcolare i ricavi totali generate da ciascun tipo di campagna**.
12. Esaminare il grafico creato da Copilot che riporta i ricavi per tipo di campagna. Questo risultato è quello desiderato, quindi selezionare il pulsante **+Aggiungi a un nuovo foglio** nella parte inferiore della finestra. In questo modo, il grafico viene aggiunto a **Foglio 3** di questo foglio di calcolo.
13. Osservando **Foglio 3**, è possibile notare come Microsoft 365 Copilot abbia incluso la tabella pivot insieme al grafico. Viene osservato che **Foglio 2** contiene la stessa tabella pivot, mentre **Foglio 3** contiene la tabella e il grafico. Poiché si desidera che **Foglio 3** contenga sia la tabella che il grafico, occorre eliminare **Foglio 2** per evitare eventuali confusioni future. Per eliminare **Foglio 2**, fare clic con il pulsante destro del mouse su di esso, selezionare **Elimina** dal menu visualizzato, quindi selezionare **OK** per confermare l'eliminazione. In questo modo, si ottengono Fogli 1 e 3.
14. Per apportare ulteriori modifiche, selezionare **Foglio 1** per tornare al foglio con la tabella pivot.
15. Ora si desidera identificare le campagne più efficaci. A tale scopo, si desidera che Copilot calcoli il ROI (ritorno sugli investimenti) per ogni campagna. Per calcolare il ROI, inserire la seguente richiesta:
    
    **Calcolare il ROI per ogni campagna**.
16. Esaminare i risultati di questa richiesta. Copilot presenta il calcolo ed è possibile selezionare l'opzione **Spiega formula** per ottenere una spiegazione del calcolo del ROI. Se si desidera che Copilot aggiunga il ROI al foglio di calcolo, selezionare il pulsante **+Inserisci colonna** visualizzato nella parte inferiore della finestra.
17. Prendere nota dei risultati. Copilot ha aggiunto una nuova colonna contenente il ROI per ogni singola campagna. Anche se va bene, si desidera determinare il ROI per ogni tipo di campagna. È stato notato l'errore quando si è rivisto il messaggio precedente. È stato chiesto a Copilot di calcolare il ROI per ogni campagna, mentre in realtà si voleva calcolare il ROI per ogni tipo di campagna. Immettere la seguente richiesta per calcolare il ROI per ogni tipo di campagna:
    
    **La modifica è positiva. Tuttavia, vorrei che calcolassi anche il ROI per ogni tipo di campagna**.
18. Esaminare i risultati. Copilot ha creato un grafico che mostra il ROI per tipo di campagna. Selezionare l'opzione nella parte inferiore della finestra per **+Aggiungere a un nuovo foglio**. In questo modo, viene aggiunta la tabella a un nuovo **Foglio 2** di questo foglio di calcolo. Oltre al grafico a barre raggruppate creato (passare il cursore sul grafico per consultare il tipo di grafico), è stata creata anche una tabella pivot contenente il ROI per tipo di campagna. Una volta terminata la revisione dei dati, selezionare **Foglio 1**.
19. Ora si vuole che Copilot determini quali campagne sono state più efficaci nel coinvolgere gli utenti. Si ritiene che il modo migliore per visualizzare questi dati sia quello di chiedere a Copilot di creare un grafico che illustri la relazione tra il totale degli utenti targettizzati e il totale degli utenti impegnati. A tale scopo, utilizzare la richiesta seguente:
    
    **Creare un grafico che mostri quale campagna è stata più efficace nel coinvolgere gli utenti**.
20. Esaminare i risultati. Copilot ha creato un grafico a barre **Utenti coinvolti per nome campagna**. Tuttavia, nel caso in cui Copilot si limiti a riassumere il totale degli utenti impegnati per campagna, non è esattamente il risultato desiderato. Per correggere questo risultato, immettere la seguente richiesta:
    
    **Questo tipo di grafico non è quello desiderato. Creare un grafico che visualizzi la relazione tra gli utenti totali targettizzati e gli utenti totali coinvolti**.
21. Esaminare i risultati. Durante i test, Microsoft 365 Copilot ha indicato che non era in grado di creare un grafico a dispersione con tali dati. Tuttavia, ha descritto la tabella pivot creata. Si ritiene che questo risultato sia sufficiente per il momento, quindi viene selezionato il pulsante **+Aggiungi a un nuovo foglio** nella parte inferiore della finestra della tabella pivot. In questo modo viene aggiunta la tabella al **Foglio 4** di questo foglio di calcolo. Dopo aver esaminato questi dati, selezionare **foglio 1**.
22. È necessario che Copilot fornisca un ultimo dato. Si desidera che Copilot identifichi le campagne più performanti in base ai ricavi generati. È quindi possibile usare queste informazioni per identificare le campagne più redditizie. Immettere il prompt seguente:
    
    **Identificare le campagne con le migliori prestazioni in base ai ricavi generati**.
23. Esaminare i risultati. Copilot ha creato un grafico che mostra i ricavi per nome della campagna. Selezionare l'opzione nella parte inferiore della finestra per **+Aggiungere a un nuovo foglio**. In questo modo, questa tabella viene aggiunta al **foglio 5** del foglio di calcolo. Oltre al grafico a barre raggruppate creato, ha creato anche una tabella pivot che mostra i ricavi totali per campagna. Dopo aver esaminato questi dati, selezionare **foglio 1**.
24. Ciò completa i dati che si vuole far analizzare da Copilot per l'utente. Tuttavia, si è curiosi di sapere quali altri suggerimenti Copilot potrebbe avere per analizzare ulteriormente i dati della campagna. Nell'elenco di richieste predefinite visualizzate sopra il campo della richiesta, cercare un suggerimento intitolato **Mostra suggerimenti per le colonne della formula**. Se viene visualizzato questo suggerimento, selezionarlo ora. Tuttavia, se non viene visualizzato questo suggerimento, immetterlo manualmente nel campo della richiesta.
25. Esaminare il suggerimento della colonna. Per aggiungerlo al foglio di calcolo, selezionare il pulsante **+Inserisci colonna**. Se viene visualizzata una richiesta predefinita che indica **Invia un altro suggerimento**, selezionarla ora. Tuttavia, se questa richiesta predefinita non viene visualizzata, immetterla manualmente nel campo della richiesta (durante i nostri test, questa richiesta predefinita viene talvolta visualizzata prima di inserire la colonna, ma poi scompare dopo l'inserimento della colonna).
26. Ripetere il passaggio precedente alcune volte per fare in modo che Copilot suggerisca calcoli diversi. Inserire quelli che piacciono e ignorare quelli che non piacciono.
27. Si vuole ora che Copilot mostri altri grafici che visualizzano vari tipi di dati. Nell'elenco delle richieste predefinite, selezionare il pulsante **Mostra informazioni dettagliate sui dati**.
28. Esaminare i risultati. Se questo grafico è di interesse, selezionare il pulsante **+Aggiungi a un nuovo foglio** e quindi tornare al **foglio 1**.
29. Selezionare quindi il pulsante **È possibile visualizzare un'altra informazione?**. Anche in questo caso, se questo grafico è di interesse, selezionare il pulsante **+Aggiungi a un nuovo foglio** e quindi tornare al **foglio 1**.
30. Dopo aver visto questi primi due grafici, ci si rende conto che si desiderano i vari grafici forniti da Copilot. Invece di esaminare più grafici uno alla volta, si vuole che Copilot aggiunga al foglio di calcolo tutte le informazioni dettagliate che è possibile creare in base ai dati. Nelle richieste predefinite, selezionare la richiesta **Aggiungi tutte le informazioni dettagliate alla griglia**.
31. Esaminare i risultati. Copilot ha creato più grafici nel foglio finale, insieme a diverse tabelle pivot. Si determina che l'analisi è stata completata in base a tutti i dati forniti da Microsoft 365 Copilot in Excel. Poiché Excel ha salvato automaticamente il file, chiudere la scheda del browser Microsoft Edge.
