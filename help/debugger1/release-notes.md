---
description: Note sulla versione di Experience Cloud Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;release notes
seo-description: Note sulla versione di Experience Cloud Debugger
seo-title: Note sulla versione
title: Note sulla versione
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: ht
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: ht
source-wordcount: '723'
ht-degree: 100%

---


# Note sulla versione {#release-notes}

## Note sulla versione {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Versione 0.0.817 del 17 maggio 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

## Nuove funzionalità {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funzione </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Dati hit post-elaborazione </p> </td> 
   <td colname="col2"> <p> Aggiunta la possibilità di <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"> visualizzare i valori sugli hit di Analytics dopo l’esecuzione delle regole di elaborazione</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Versione 0.0.810 del 6 marzo 2019 {#topic-83bb7ddd68594177be9fd7826b650b80}

## Nuove funzionalità {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funzione </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Test di Adobe Experience Platform Auditor </p> </td> 
   <td colname="col2"> <p> A Experience Cloud Debugger sono stati aggiunti i <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local">test di Platform Auditor</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Experience Cloud Debugger ora visualizza le risposte di AAM. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Correzioni di bug {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* È stato corretto un problema a causa del quale il piè di pagina nascondeva il contenuto nella parte inferiore della pagina.

* È stato aggiornato il piè di pagina di Experience Cloud Debugger.
* È stato risolto un problema per cui per Target veniva utilizzata terminologia obsoleta.

## Versione 0.0.809 del 28 febbraio 2019 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## Nuove funzionalità {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funzione </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Funzioni del codice di incorporamento </p> </td> 
   <td colname="col2"> <p> Dividi, sostituisci e inserisci funzioni del codice di incorporamento. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Miglioramenti {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* È stata risolta una potenziale vulnerabilità causata da un input utente non bonificato.

## Correzioni di bug {#section-556417ff055848c1bf037354dd43cbd0}

* È stato risolto un problema per cui gli eventi AAM DIL non venivano acquisiti nella scheda AAM.

* È stato risolto un problema in Inserisci Launch in modo dinamico, a causa del quale l’interfaccia utente sembrava mappare un codice da incorporare diverso quando non lo era.
* È stato risolto un problema in Inserisci Launch in modo dinamico a causa del quale continuava a essere visualizzato un URL errato.
* È stato risolto un problema a causa del quale Experience Cloud Debugger continuava a sostituire i codici da incorporare anche quando la finestra di Experience Cloud Debugger era chiusa.

## Versione 0.0.806 del 10 settembre 2018 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## Nuove funzionalità {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funzione </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Collegamento Analytics nella scheda Strumenti </p> </td> 
   <td colname="col2"> <p>Mostra nomi descrittivi per evar/prop tramite API di Analytics tramite l’accesso IMS. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Inserisci Launch in modo dinamico </p> </td> 
   <td colname="col2"> <p>Dalla scheda Strumenti, è possibile inserire in modo dinamico Adobe Experience Platform Launch in qualsiasi pagina per eseguire un test su una pagina in cui non è installato Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Miglioramenti di Target </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Sono stati aggiunti orari di prestazioni per le richieste Target. </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">Cattura di adobe.target.trackEvent. </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Miglioramenti {#section-56003a12c32f4998bf1cf2a25a518592}

* È stata migliorata la visualizzazione della scheda Rete in modo che l’altezza della tabella non sia troppo grande e che l’utente debba scorrere in verticale prima che sia possibile scorrere in orizzontale. In precedenza, le barre di scorrimento venivano visualizzate nella parte inferiore della tabella. Poiché la tabella poteva diventare molto grande, gli utenti dovevano scorrere verticalmente fino in fondo per visualizzarla.
* È stato aggiornato il collegamento a ObservePoint dalla scheda Strumenti.

## Correzioni di bug {#section-d9231f5c77254d0888347e5f569a8b1d}

* È stato risolto un problema per il quale la scheda Experience Cloud non veniva aggiornata.

* È stato risolto un problema che causava la visualizzazione di “Media Optimizer” nella riga Soluzione della scheda Rete, invece del nome corrente di “Advertising Cloud”.
* È stato risolto un problema a causa del quale Experience Cloud Debugger inseriva _satellite in ogni pagina.

## Versione 0.0.803 del 10 agosto 2018 {#topic-d2901fb70ce04a5586f6c7a994fce875}

La versione 0.0.803 non include modifiche rivolte ai clienti.

## Versione 0.0.802 del 1 agosto 2018 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## Nuove funzionalità {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funzione </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Collegamento a Platform Auditor nella scheda Strumenti </p> </td> 
   <td colname="col2"> <p>È stato aggiunto un collegamento a Platform Auditor da Experience Cloud Debugger. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Schede compresse </p> </td> 
   <td colname="col2"> <p>Le schede compresse persistono nelle schede Riepilogo e Strumento. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Fai clic per visualizzare </p> </td> 
   <td colname="col2"> <p> Funzionalità di clic per visualizzare tutte le schede. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Miglioramenti {#section-0e7090e3e6a645f085d4553b983ecff8}

* Nome di Media Optimizer modificato in Advertising Cloud.
* Soluzioni rimosse dalla scheda Rete se non trovate.

## Correzioni di bug {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* È stato risolto un problema per cui la funzione “Fai clic sulla cella per visualizzare” non veniva aggiornata.
* È stato risolto un problema per cui gli hit AAM non venivano visualizzati nella scheda AAM

## Versione 0.0.798 del 14 giugno 2018 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## Nuove funzionalità {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funzione </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Opzione esporta di Excel </p> </td> 
   <td colname="col2"> <p>Opzione esporta Excel aggiunta alla scheda Rete. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aspetto migliorato </p> </td> 
   <td colname="col2"> <p>È stato aggiornato il font dell’estensione Chrome in Adobe Clean. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Funzionalità sfiora del touchpad </p> </td> 
   <td colname="col2"> <p>Funzionalità sfiora del touchpad avanti/dietro disattivata. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Indicatore di chiamata server non elaborato </p> </td> 
   <td colname="col2"> <p>È stato aggiunto un indicatore di copia della stringa non elaborata di chiamata del server. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Pulizia scheda Registri </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">Nascondi le soluzioni nel filtro Soluzioni se nei registri non sono presenti elementi di riga per tale soluzione. </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">Nascondi il Filtro di Livello se non viene trovata alcuna chiamata DTM, perché si applica solo a DTM. </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">Modifica le icone visualizzate nella colonna Livello in modo che non risultino cliccabili quando non si fa clic su di esse. </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">Formattazione standard di “Mostra codice” sugli elementi riga DTM. </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aggiorna collegamento della guida nel piè di pagina </p> </td> 
   <td colname="col2"> <p>Aggiorna il collegamento della guida nel piè di pagina in modo che rimandi a <a href="https://docs.adobe.com/content/help/it-IT/debugger/using/experience-cloud-debugger.html" format="https" scope="external">https://docs.adobe.com/content/help/it-IT/debugger/using/experience-cloud-debugger.html</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Correzioni di bug {#section-c292cf7dcb17463bb1928de73bd55121}

* È stato risolto un problema per il quale il numero del contrassegno non veniva cancellato.
* È stato risolto un problema per il quale il cliente segnalava dettagli di riepilogo vuoti.

## Versione 0.0.797 del 25 maggio 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

## Nuove funzionalità {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funzione </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Opzioni per mbox </p> </td> 
   <td colname="col2"> <p>Sono state aggiunte opzioni per mbox alla scheda Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Le impostazioni del filtro ora sono permanenti </p> </td> 
   <td colname="col2"> <p>Le impostazioni del filtro ora si trovano nella parte superiore dello schermo nelle schede di rete e di registro. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Visualizza e copia i valori di rete </p> </td> 
   <td colname="col2"> <p>Puoi visualizzare i dettagli e copiare il valore di qualsiasi cella nella scheda di rete. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Collegamenti piè di pagina legali e copyright </p> </td> 
   <td colname="col2"> <p>All’interfaccia utente sono stati aggiunti collegamenti a piè di pagina e informazioni sul copyright legali. </p> </td> 
  </tr> 
 </tbody> 
</table>

