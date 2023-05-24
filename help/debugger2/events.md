---
description: Scopri come utilizzare la scheda Eventi in Adobe Experience Platform Debugger.
keywords: debugger;estensione debugger di experience platform;chrome;estensione;eventi;dtm;target
seo-description: Experience Platform Debugger Events Screen
seo-title: Events
title: Scheda Eventi
exl-id: 1f94ca36-d545-4e41-89a9-ed97c45991fb
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 42%

---

# Scheda Eventi

Il **Eventi** fornisce una visualizzazione grafica degli eventi che si verificano, visualizzati su una timeline.

![](assets/events.jpg)

Per ogni evento, nella sequenza temporale viene visualizzata un’icona per la soluzione applicabile. Le icone mostrano anche le modifiche apportate al livello dati (se attivato). Passa il puntatore del mouse sopra un’icona per visualizzare un riepilogo dell’evento. Seleziona l’evento per ulteriori dettagli. Per visualizzare più eventi, premi Maiusc-Seleziona o Ctrl-Seleziona.

![](assets/events-details.jpg)

Seleziona un dettaglio per ulteriori informazioni.

![](assets/events-details-more.jpg)

## Rileva modifiche apportate al livello dati

Per abilitare il tracciamento delle modifiche al livello dei dati nella sequenza temporale:

1. Seleziona l’icona a forma di ingranaggio in alto a destra.
1. Inserisci il nome del livello dati.

   ![](assets/event-datalayer.jpg)

1. Seleziona **[!UICONTROL Save]**.

I dettagli delle modifiche mostrano tutti gli elementi che sono stati eliminati o aggiunti al livello dati. Puoi selezionare **{}** per avere più informazioni sul livello dati.

## Scarica le informazioni sull’evento

Seleziona **[!UICONTROL Download]** per scaricare un file Excel con le informazioni sulle chiamate effettuate da una pagina.
