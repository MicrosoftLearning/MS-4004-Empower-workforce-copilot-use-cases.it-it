# Creare un report di analisi finanziaria usando Microsoft 365 Copilot in Word
---
Microsoft 365 Copilot in Word può aiutare i professionisti finanziari a creare documenti in modo più efficiente. Può aiutarli a scrivere contenuti, argomenti di ricerca e trasformare il contenuto esistente in un documento di cui possono essere orgogliosi. Copilot può anche far risparmiare tempo e pensieri riscrivendo e modificando documenti.

Ad esempio, se si è un analista finanziario e si deve scrivere un report sulle prestazioni di un'azienda, è possibile usare Microsoft 365 Copilot in Word per creare una bozza del report. È possibile indicare a Copilot di "Scrivere un report sulle prestazioni finanziarie della società XYZ" e genererà una bozza che è possibile perfezionare. È possibile porre domande su Copilot Chat per cercare, ideare o scorrere il contenuto da aggiungere.

Se si lavora a un documento esistente, Copilot può aiutare a riscrivere e modificare il documento, risparmiando tempo e pensieri. In questo esercizio, si indica a Microsoft 365 Copilot in Word di scrivere un nuovo report in base ai dati del foglio di calcolo della campagna di marketing del primo trimestre di Fabrikam analizzato e aggiornato nell'esercizio precedente. Tuttavia, invece di usare il foglio di calcolo di Excel, si user un documento di Word che contiene tutti i dati del foglio di calcolo.

> **NOTA:** Microsoft 365 Copilot in Word può creare un report basato su un foglio di calcolo. Tuttavia, non è possibile fare riferimento direttamente a un file di Excel dall'interno di Word. È invece necessario copiare e incollare i dati dal file di Excel in un documento di Word. Quando i dati si trovano in un documento di Word, è possibile usare Copilot per generare un report basato su tali dati. In questo esercizio i dati del foglio di calcolo usati nell'esercizio precedente sono stati copiati e incollati in un documento di Word denominato **Dati della campagna di marketing del primo trimestre di Fabrikam**.

> **SUGGERIMENTO:** quando si lavora in Copilot, se restituisce un messaggio di errore di qualsiasi tipo, inviare nuovamente la richiesta. In questo modo viene spesso risolto il problema. Analogamente, i dati non vengono presentati correttamente (ad esempio i dati della tabella visualizzati nel codice HTML anziché in una tabella di Word), quindi immettere una richiesta a Copilot di correggere i dati e presentarli correttamente (ad esempio: **le tabelle pivot vengono visualizzate tutte nel codice HTML. Convertire queste tabelle in un formato di tabella in Word).**

### Esercizio

In qualità di Direttore finanziario di Fabrikam, è stato usato Microsoft 365 Copilot in Excel per analizzare l'efficacia delle campagne di marketing del primo trimestre dell'azienda nell'esercizio precedente. In questo esercizio si prevede di usare Microsoft 365 Copilot in Word per generare un report che riepiloga l'analisi di quei dati. Il foglio di calcolo è stato copiato e incollato automaticamente in un documento di Word, che verrà scaricato nel primo passaggio.

1.  Selezionare il collegamento seguente per scaricare i [dati della campagna di marketing del primo trimestre di Fabrikam](https://go.microsoft.com/fwlink/?linkid=2268926).
2.  Al termine del download, spostare il file nell'account OneDrive e quindi aprire e chiudere il file per ottenerlo nell'elenco dei file usati più di recente .
3.  Se si ha una scheda **Microsoft 365** aperta nel browser Microsoft Edge, selezionarla ora. In caso contrario, aprire una nuova scheda e immettere l'URL seguente: **https://www.office.com**
4.  In **Microsoft 365** aprire **Microsoft Word** e quindi aprire un documento vuoto.
5.  Nella finestra **Crea una bozza con Copilot** visualizzata nella parte superiore del documento vuoto immettere la richiesta seguente, ma non selezionare il pulsante **Genera** finché non si collega il file alla richiesta nel passaggio successivo:
    
    **Sono il direttore finanziario di Fabrikam. Creare un report di analisi delle campagne di marketing del primo trimestre in base al file allegato, che fornisce i dati sulle campagne di marketing del primo trimestre. Includere le sezioni seguenti nel report: Riepilogo esecutivo, Analisi dei dati ed Elementi consigliati**.
6.  È ora necessario allegare alla richiesta il file scaricato **Dati della campagna di marketing del primo trimestre di Fabrikam.docx**. Nella finestra **Bozza con Copilot**, selezionare il pulsante **Fare riferimento al contenuto**. Nel menu a discesa visualizzato, se il file **Dati della campagna di marketing del primo trimestre di Fabrikam.docx** viene visualizzate nell'elenco dei file, selezionarlo. In caso contrario, selezionare **Sfoglia file dal cloud**, selezionare il file dall'elenco file **Recenti** e quindi selezionare il pulsante **Allega** . Se il file non viene visualizzato nell'elenco **File recenti**, selezionare **I miei file** nella parte superiore del pannello di navigazione nella finestra **Preleva un file**, passare alla cartella in cui è archiviato il file, selezionare il file e quindi selezionare **Allega**. Notare come il file viene visualizzato nella richiesta.
7.  Selezionare **Genera**. In questo caso, Copilot estrae le informazioni pertinenti dal file e crea una bozza di report che analizza i dati.
8.  Esaminare i risultati. Se i dati nella **sezione Riepilogo esecutivo** vengono presentati in un elenco puntato, immettere la richiesta seguente e sostituire **\{la tabella o l'elenco puntato**\} con la **tabella**. Se i dati di **Riepilogo esecutivo** non sono in formato elenco puntato, immettere ila richiesta seguente e sostituire **\{tabella o elenco puntato\}** con **elenco puntato**:
    
    **Convertire le informazioni nella sezione Riepilogo esecutivo in un formato \{tabella o elenco  puntato\}**.
9.  Se la sezione **Analisi dei dati** è già in formato tabella, procedere con il passaggio successivo. In caso contrario, immettere ila richiesta seguente per inserire i dati in una tabella in modo che sia più facile da leggere:
    
    **Convertire le informazioni nella sezione Analisi dati in un formato di tabella**.
10. Esaminare la tabella dei dati nella sezione **Analisi dei dati**. Vediamo se Copilot può rimuovere una colonna di dati da una tabella. Immettere la richiesta seguente e sostituire l'\{intestazione\} con il nome di una colonna da rimuovere:
    
    **Nella tabella dei dati nella sezione Analisi dei dati rimuovere la colonna dell'\{intestazione\}**.
11. Le **Raccomandazioni** piacciono, ma si ritiene che sarebbero più utili se Copilot visualizzasse i dati in ordine di importanza. Immettere la richiesta seguente per far apportare questa modifica a Copilot:
    
    **Nella sezione Raccomandazioni visualizzare gli elementi in ordine di importanza, a partire dall'elemento più importante**.
12. Dopo aver esaminato questa bozza più recente, l'utente è soddisfatto del report ed è pronto a salvarlo. Nella finestra Copilot in fondo al documento, selezionare il pulsante **Mantieni** per convertirlo da bozza di Copilot a documento di Word.
13. Rivedere il documento. Una volta soddisfatti, è possibile eliminare il documento o salvarlo in OneDrive per riferimento futuro.
14. Chiudere questa scheda nel browser Microsoft Edge.
