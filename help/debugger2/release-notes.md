---
title: Note sulla versione
description: Note aggiornate sulla versione di Adobe Experience Platform Debugger.
keywords: debugger;estensione Experience Platform Debugger;chrome;estensione;note sulla versione
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 4%

---

# Note sulla versione

## Versione 1.3.0 - 28 gennaio 2022

* È stato aggiunto il collegamento Informazioni su, che consente di visualizzare la versione corrente e le relative note.
* È stata aggiunta l’opzione per visualizzare gli hit post-elaborati per le richieste di Analytics. L’interruttore è disponibile nella sezione Analytics.
* È stato risolto un problema di sessione di debug remoto che si verificava alla chiusura della sessione all’esterno del debugger.
* È stata corretta la notifica di errore visibile nella scheda Transazioni Edge dell’SDK Web.
* È stato corretto l’avviso di deprecazione dei tag di Adobe nella pagina quando il debugger accedeva all’oggetto _satellite.
* Sono stati risolti alcuni casi in cui un’istanza AppMeasurement non veniva trovata nella pagina.
* È stato risolto un problema di connessione alla pagina che si verificava alla prima apertura della finestra del debugger.

## Versione 1.2.0 - 26 ottobre 2021

* Mostra gli eventi da tutte le schede del browser nella visualizzazione di rete. Per visualizzare solo gli eventi della scheda corrente, seleziona l’icona a forma di lucchetto nell’angolo inferiore destro del debugger.
* Branding aggiornato.

## Versione 1.1.0 - 5 ottobre 2021

* Visualizzazione debug remoto: organizza gli eventi di debug remoto in un diagramma di flusso visivo nella sezione Adobe Experience Platform Web SDK > Transazioni Edge.
* Richiedi che l’organizzazione IMS Adobe Experience Platform Web SDK utilizzata nella pagina corrisponda all’organizzazione registrata all’avvio di una nuova sessione di debug remoto.
* Mostra solo le transazioni edge per la scheda connessa. I registri di traccia di Target sono ancora disponibili nella sezione Registri > Edge.
* Consenti la sostituzione della configurazione ID flusso di dati separata per ogni istanza di Adobe Experience Platform Web SDK sulla pagina. Attiva/disattiva l’opzione Aggiungi debug abilitato.
* È stato risolto un problema a causa del quale il token di traccia di Adobe Target non veniva sempre inviato con sessioni di debug remoto per Adobe Experience Platform Web SDK.

## Versione 1.0.0 del 5 maggio 2021

* Prima versione principale di Experience Platform Debugger. Destinato a sostituire il Experience Cloud Debugger.
