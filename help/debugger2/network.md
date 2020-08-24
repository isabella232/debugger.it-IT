---
description: Schermata Rete di Experience Cloud Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;network;information
seo-description: Schermata Rete di Experience Cloud Debugger
seo-title: Informazioni di Rete
title: Informazioni di Rete
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: ht
source-git-commit: 1d81f427e2c1a68a182fae8262d0e2ad32a87223
workflow-type: ht
source-wordcount: '228'
ht-degree: 100%

---


# Rete {#network}

>[!IMPORTANT]
>
>Adobe Experience Cloud Cloud Debugger 2.0 è attualmente in versione beta. La documentazione e la funzionalità sono soggette a modifiche.

Per visualizzare le informazioni di Rete, fai clic su **[!UICONTROL Network]**.

La schermata Rete raccoglie tutte le chiamate della soluzione Adobe Experience Cloud effettuate sulla pagina e le visualizza in ordine da sinistra a destra. I parametri standard vengono etichettati automaticamente con nomi descrittivi e disposti per raggruppare parametri comuni sullo stesso ruolo.

![](assets/network.jpg)

Questa schermata è utile per confrontare coppie di valori chiave tra i diversi riscontri. Puoi verificare che i parametri utilizzati per le integrazioni, come Experience Cloud Visitor ID o Supplemental Data ID, siano coerenti tra le diverse integrazioni.

>[!NOTE]
>
>Al momento, non tutti i parametri passati nelle chiamate della soluzione (ad esempio, variabili di contesto di Analytics, parametri personalizzati di Target o ID cliente del servizio Experience Cloud ID) sono visibili nella schermata Rete.

Per cambiare le informazioni in base alla soluzione, seleziona la soluzione da visualizzare dall’elenco nella barra di navigazione a sinistra. Nell’esempio seguente il filtro è impostato in modo da mostrare solo Analytics:

![](assets/network-analytics.jpg)

Per visualizzare di nuovo tutte le soluzioni, fai clic su **[!UICONTROL Network]**.

Fai clic su un elemento nella visualizzazione di Rete per ingrandirlo. Dalla finestra di visualizzazione espansa, puoi copiare le informazioni visualizzate negli Appunti.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Per cancellare l’elenco, fai clic su **[!UICONTROL Remove Events]**.

Per scaricare un file Excel con le informazioni di questa schermata, fai clic su **[!UICONTROL Download]**.