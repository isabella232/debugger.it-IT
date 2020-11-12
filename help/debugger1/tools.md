---
description: Schermata Strumenti di Experience Cloud Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: Schermata Strumenti di Experience Cloud Debugger
seo-title: Strumenti
title: Strumenti
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '392'
ht-degree: 92%

---


# Strumenti {#tools}

Nella schermata Strumenti, puoi attivare o disattivare vari strumenti per la soluzione installata. Ad esempio, puoi attivare le istruzioni di debug della console di Target o utilizzare la DTM Staging Library. Questi strumenti sono disponibili solo se Target e DTM sono installati sulla pagina.

![](assets/tools.jpg)

Puoi inserire dinamicamente  Adobe Experience Platform Launch o DTM su qualsiasi pagina per eseguire il test su una pagina in cui non è installato Platform Launch o DTM. Fai clic sull’icona **[!UICONTROL Embed Code]**, digita il [codice di incorporamento](https://docs.adobe.com/content/help/it-IT/dtm/using/client-side/deployment.html) e fai clic su **[!UICONTROL Save]**.

![](assets/tools-embedcode.jpg)

## Informazioni su DTM {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Strumento </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> Registrazione console DTM </p> </td> 
   <td colname="col2"> <p>Questo strumento espone le istruzioni di debug specifiche di DTM alla console del browser. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Uso della libreria Staging </p> </td> 
   <td colname="col2"> <p>Questo strumento utilizza la libreria Gestione temporanea per le informazioni di debug DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Disattiva DTM </p> </td> 
   <td colname="col2"> <p>Questo strumento blocca il controllo delle informazioni di DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Inserimento dinamico DTM </p> </td> 
   <td colname="col2"> <p> Questo strumento consente di inserire il codice DTM nella pagina. Utilizza l’editor del codice di incorporamento per modificare il codice inserito. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Informazioni su Target {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Strumento </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Registrazione della console di Target </p> </td> 
   <td colname="col2"> <p>Questo strumento mostra le istruzioni di debug specifiche di Target alla console del browser, che iniziano tutte con il prefisso <span class="codeph"> AT:</span>, mediante l’aggiunta di un cookie denominato <span class="codeph"> mboxDebug=true</span> al browser. Al momento, le istruzioni della console non vengono visualizzate nella schermata Registri di Debugger, ma sono visibili nella console di debug nativa del browser. </p> <p> Questo strumento richiede at.js 0.9.6+. Se utilizzi una versione precedente di at.js, puoi aggiungere all’URL il parametro della stringa di query <span class="codeph"> ?mboxDebug=true</span> per attivare la registrazione della console. Se utilizzi mbox.js, puoi aggiungere il parametro <span class="codeph"> ?_AT_Debug=console</span> per attivare la registrazione della console limitata alle attività di Visual Experience Composer (Compositore esperienza visivo). </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Abilita tracce Mbox </p> </td> 
   <td colname="col2"> <p>Questo strumento aggiunge informazioni dettagliate alle risposte Target, che possono essere visualizzate nella schermata <span class="uicontrol"> Target&gt;Mbox Trace</span> del debugger. </p> <p> Devi aver effettuato l’accesso a Experience Cloud in una delle tue schede Chrome per abilitare questo strumento. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Disattiva Target </p> </td> 
   <td colname="col2"> <p>Questo strumento disattiva tutte le richieste Target aggiungendo al browser un cookie denominato <span class="codeph"> mboxDisable=true</span>. </p> <p> Questo strumento richiede at.js 0.9.6+. Se utilizzi una versione precedente, puoi aggiungere all’URL il parametro della stringa di query <span class="codeph">?mboxDisable=true </span>per disabilitare le mbox. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Evidenziazione mbox </p> </td> 
   <td colname="col2"> <p> Questo strumento disegna una casella rossa intorno alle mbox precedenti in stile wrapping. </p> </td> 
  </tr> 
 </tbody> 
</table>

Nel video seguente viene illustrato come utilizzare l’estensione Debugger con Adobe Target.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/)
