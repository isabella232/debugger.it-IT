---
description: Debugger esamina le pagine web e aiuta a individuare i problemi relativi all’implementazione delle soluzioni Experience Cloud
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: '‘Documentazione tecnica per l’estensione Adobe Experience Cloud Debugger 2.0 Chrome e Firefox: esamina le pagine web e illustra i problemi con le implementazioni delle soluzioni Experience Cloud’'
seo-title: Estensione Adobe Experience Platform Debugger per Chrome e Firefox
title: Estensione Adobe Experience Platform Debugger
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: ht
source-git-commit: 3dc1876c0516b7a81f68a207c6a1651bc95b17ab

---


# (Beta) Adobe Experience Platform Debugger 2.0 {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Cloud Cloud Debugger 2.0 è attualmente in versione beta. La documentazione e la funzionalità sono soggette a modifiche.

[Adobe Experience Platform Debugger per Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) e [Firefox](https://addons.mozilla.org/it/firefox/addon/adobe-experience-platform-dbg/) esamina le pagine web e ti aiuta a individuare problemi nell’implementazione delle soluzioni Experience Cloud.

Utilizza Adobe Experience Platform Debugger con le altre soluzioni di attivazione Adobe per un flusso di lavoro come indicato di seguito:

1. Utilizza [Launch](https://docs.adobe.com/content/help/it-IT/launch/using/overview.html) o [DTM](https://docs.adobe.com/content/help/it-IT/dtm/using/dtm-home.html) per inserire il codice necessario per attivare le soluzioni [Adobe Experience Cloud](https://docs.adobe.com/content/help/it-IT/core-services/interface/experience-cloud.html) nelle tue pagine.

1. Utilizza [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) per testare le tue implementazioni.
1. Utilizza Adobe Experience Platform Debugger per eseguire il debug dei problemi rilevati da Auditor o per esaminare altre informazioni sulle implementazioni.

Non è necessario eseguire i passaggi di cui sopra in tale ordine, ma si tratta della procedura comune.

Anche se puoi eseguire il debugger su qualsiasi pagina web, i dati non pubblici sono disponibili nell’estensione solo se sei autenticato in Experience Cloud in una delle schede Chrome aperte.

## Casi d’uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Usa Debugger per raccogliere informazioni utili per comprendere come vengono implementate le soluzioni Experience Cloud. Ad esempio:

* **Launch:** consulta quali proprietà, ambiente e build sono implementati in una pagina.
* **Target:** scopri le attività per le quali hai o meno diritto e perché.
