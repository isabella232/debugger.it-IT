---
description: nulle
keywords: debugger;experience cloud debugger extension;chrome;extension;network;information
seo-description: 'null'
seo-title: Informazioni di Rete
title: Informazioni di Rete
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: tm+mt
source-git-commit: 2c3d056451c5b7b4bf5603c22bf3bbdbc693491f

---


# Informazioni di rete {#network-information}

To view Network information, click **[!UICONTROL Network]**.

La schermata Rete raccoglie tutte le chiamate della soluzione Adobe Experience Cloud effettuate sulla pagina e le visualizza in ordine da sinistra a destra. I parametri standard vengono etichettati automaticamente con nomi descrittivi e disposti per raggruppare parametri comuni sullo stesso ruolo.

![](assets/network.jpg)

Questa schermata è utile per confrontare coppie di valori chiave tra hit. Puoi confermare che i parametri utilizzati per le integrazioni, ad esempio Experience Cloud Visitor ID o Supplemental Data ID, sono coerenti tra le diverse integrazioni.

>[!NOTE]
>
>Al momento, non tutti i parametri passati nelle chiamate della soluzione (ad esempio, variabili di contesto di Analytics, parametri personalizzati di Target o ID cliente del servizio Experience Cloud ID) sono visibili nella schermata Rete.

Per filtrare le informazioni per soluzione, selezionate la soluzione da visualizzare dall'elenco nella barra di navigazione a sinistra. L'esempio seguente viene filtrato per mostrare solo Analytics:

![](assets/network-analytics.jpg)

Per tornare alla visualizzazione di tutte le soluzioni, fate clic su **[!UICONTROL Network]**

Fare clic su un elemento nella visualizzazione Rete per visualizzare una visualizzazione espansa. Dalla finestra di visualizzazione espansa, puoi copiare le informazioni visualizzate negli Appunti.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Per cancellare l'elenco, fare clic su **[!UICONTROL Remove Events]**.

Per scaricare un file Excel contenente le informazioni su questa schermata, fate clic su **[!UICONTROL Download]**.