---
description: Utilizzo delle schede Soluzione in Adobe Debugger
keywords: debugger;esperienza estensione del debugger cloud;cromo;estensione;riepilogo;lima;richieste;soluzioni;informazioni;analisi;target;audience manager;media Optimizer;amo;id service
seo-description: Utilizzo delle schede Soluzione in Adobe Debugger
seo-title: Schede della soluzione in Adobe Debugger
title: Schede della soluzione
uuid: 5e999ef2-6399-4ab5-a841-3a839d081728
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Schede della soluzione{#solution-tabs}

Fai clic sulle schede della soluzione per visualizzare i risultati per specifiche soluzioni Adobe Experience Cloud.

## Analytics {#section-f71dfcc22bb44c86bec328491606a482}

La scheda Analisi fornisce informazioni sull'implementazione di [Analytics](https://experiencecloud.adobe.com/resources/help/en_US/reference/) .

**Hit**

Per impostazione predefinita, tutte le chiamate server effettuate alla stessa suite di rapporti sono compresse.

![](assets/analytics-hits.jpg)

**** Scarica: Scarica informazioni su tutte le suite di rapporti visualizzate come foglio di calcolo Excel.

**** Cancella tutte le richieste: Rimuovere tutte le richieste visualizzate dalla visualizzazione Analytics. Dopo aver cancellato le richieste, le nuove richieste verranno visualizzate quando si verificano.

Fai clic sull’ID suite di rapporti per espandere la visualizzazione:

![](assets/analytics-hits-expand.jpg)

In questa schermata vengono visualizzate tutte le richieste dall'apertura del debugger o dall'eliminazione delle richieste. I parametri predefiniti vengono mappati automaticamente a nomi descrittivi. [Le variabili prop ed eVar](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/props_eVars.html) possono essere mappate ai vostri nomi descrittivi personalizzati (ad esempio, "prop1" potrebbe essere visualizzato come "Tipo utente") se eseguite l'autenticazione utilizzando la funzione "Link Analytics" (vedi sotto). Le richieste vengono visualizzate in sequenza da sinistra a destra.

**** Scarica: Salva tutte le richieste effettuate nella suite di rapporti come foglio di calcolo Excel.

**** Richieste chiare: Rimuovi tutte le richieste effettuate a questa suite di rapporti. Le nuove richieste vengono visualizzate nel momento in cui si verificano.

**Account collegati (legacy)**

Fai clic su **[!UICONTROL Collega account]**, quindi immetti le informazioni richieste per collegare un account Analytics al Debugger.

>[!NOTE]
>
>Attualmente, questa funzione è supportata solo per le credenziali di accesso legacy degli utenti Analytics.

![](assets/analytics-link-account.jpg)

**Recupera hit Post-Elaborati**

Abilita l’opzione Recupera hit post-elaborati se vuoi visualizzare i valori sugli hit di Analytics dopo l’esecuzione delle regole di elaborazione. Affinché questa funzione funzioni, devi accedere ad Adobe Experience Cloud.

Quando questa opzione è attivata, alle richieste di Analytics viene aggiunto un parametro di debug. Gli hit continuano ad essere elaborati come qualsiasi altro hit. Debugger esegue il polling dell'API di debug di Analytics per recuperare i valori delle regole di post-elaborazione per tutti gli hit con un ID hit originale. Gli hit post-elaborati hanno uno sfondo viola e sono visualizzati accanto all’hit originale.

Per la maggior parte delle implementazioni di Analytics, le informazioni sulle regole di post-elaborazione sono disponibili in pochi minuti. L'implementazione di Analytics per Target (A4T) richiede molto più tempo.

## Target {#section-988873ba5ede4317953193bd7ac5474c}

Utilizzate la scheda Target per visualizzare i dettagli delle richieste di [Target](https://docs.adobe.com/content/help/en/target/using/target-home.html) o di traccia [di](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) Mbox.

Fate clic su **[!UICONTROL Richieste]**, quindi espandete l'ambiente per visualizzare le informazioni su Target.

![](assets/target-requests.jpg)

Fate clic su **[!UICONTROL Cancella tutte le richieste]** per rimuovere le richieste attualmente visualizzate. Verranno visualizzate più richieste man mano che vengono effettuate.

Potete inoltre utilizzare il filtro Target per [abilitare la traccia MBox a scopo](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html)di debug Target.

Per abilitare Mbox Trace, devi avere una scheda Chrome aperta autenticata in Experience Cloud. Una volta attivato, viene visualizzato il nome utente dell'Adobe ID. Espandi il tuo nome utente per esporre i codici client di Target associati alle organizzazioni Experience Cloud a cui hai accesso. Fate clic sul codice client per il quale desiderate abilitare Mbox Trace e verificate che sia visualizzato il segno di spunta verde. Verranno visualizzate tutte le richieste Target con le informazioni di traccia Mbox, raggruppate per codice client. Per esplorare le informazioni di Mbox Trace, espandete la richiesta per visualizzare le schede:

* [Attività](https://docs.adobe.com/content/help/en/target/using/activities/activities.html) La scheda Attività mostra tutte le attività associate al nome della richiesta Target, indipendentemente dal fatto che si sia qualificati per l'attività. Per "Attività abbinate" si intendono le attività per le quali avete qualificato e le cui offerte sono state distribuite nella risposta. Potete espandere il nome dell'attività per confermare l'esperienza in uso e quali audience e condizioni di targeting vi hanno qualificato per l'attività. "Attività valutate" sono tutte le attività valutate, indipendentemente dal fatto che si sia qualificati. Per risolvere i problemi relativi alla non qualificazione per un'attività "Valutata" ma non "Corrispondente", espandete il nome dell'attività e controllate la sezione "Pubblico senza corrispondenza".

* Richiesta

   La scheda della richiesta di [Mbox Trace](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) è simile alla scheda della richiesta principale. Potete visualizzare tutti i parametri passati dalla richiesta Target, oltre alle intestazioni della richiesta.
* Profilo

   Espandete la sezione Snapshot profilo per visualizzare le informazioni [di](https://docs.adobe.com/content/help/en/target/using/audiences/visitor-profiles/variables-profiles-parameters-methods.html) profilo memorizzate come visitatore nel database dei profili di Target. Tutti i profili in-mbox e script sono esposti qui, oltre ad alcuni profili di sistema. La colonna Stato mostra i profili modificati nell’ambito di questa richiesta, nonché i relativi valori prima e dopo l’ingresso della richiesta nel sistema del profilo.
* Audience Manager

   Le sezioni "segmentIds" e "cachedSegmentIds" della scheda Audience Manager mostrano gli ID dei [tipi di pubblico](https://docs.adobe.com/content/help/en/target/using/audiences/target.html) condivisi da Experience Cloud a Target, e per i quali sei qualificato. Possono essere audience create in Audience Manager, Analytics o nel generatore di pubblico nel servizio core Persone. Questi ID possono essere cercati nell’interfaccia utente di Audience Manager per trovare il nome dell’audience.

Il seguente video mostra la funzionalità di Target generale:

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=ita)

Il seguente video mostra la traccia Mbox:

>[!VIDEO](https://video.tv.adobe.com/v/23113t2/?captions=ita)

## Audience Manager {#section-1d4484f8b46f457f859ba88039a9a585}

Utilizzate la scheda [Audience Manager](https://experiencecloud.adobe.com/resources/help/en_US/aam/) per visualizzare i dettagli degli [eventi](https://experiencecloud.adobe.com/resources/help/en_US/aam/dcs-event-calls.html). Fare clic sull'organizzazione per espanderla e visualizzare le informazioni.

![](assets/audience-manager.jpg)

Fate clic su **[!UICONTROL Cancella tutti gli eventi]** per ripristinare le informazioni visualizzate. I nuovi eventi verranno visualizzati nel momento in cui si verificano.

**Sincronizzazione ID**

La sincronizzazione ID è il primo passo del processo di trasferimento dati in entrata e asincrono. In questo passaggio, Audience Manager e il fornitore confrontano e confrontano gli ID per i rispettivi visitatori del sito.

![](assets/aam-idsync.jpg)

Per ulteriori informazioni, consulta Sincronizzazione [ID per trasferimenti](https://experiencecloud.adobe.com/resources/help/en_US/aam/c_id_sync_in.html) dati in entrata nella documentazione di Audience Manager.

## Advertising Cloud {#section-ee80a9c509f2462c89c1e5bd8d05d7c8}

Utilizzate la scheda Advertising Cloud per visualizzare le richieste di Advertising Cloud.

Fate clic su **[!UICONTROL Richieste]**, quindi espandete l'ambiente per visualizzare le informazioni su Advertising Cloud.

Fate clic su **[!UICONTROL Cancella tutte le richieste]** per rimuovere le richieste attualmente visualizzate. Verranno visualizzate più richieste man mano che vengono effettuate.

## Servizio Experience Cloud ID {#section-a96c32f8e63a4991abb296f6e8ea01cf}

Utilizzate la scheda Servizio Experience Cloud ID per visualizzare le richieste del servizio [](https://experiencecloud.adobe.com/resources/help/en_US/mcvid/) Experience Cloud ID.

Fai clic su **[!UICONTROL Richieste]**, quindi espandi l’ambiente per visualizzare informazioni sul servizio Experience Cloud ID.

Fate clic su **[!UICONTROL Cancella tutte le richieste]** per rimuovere le richieste attualmente visualizzate. Verranno visualizzate più richieste man mano che vengono effettuate.
