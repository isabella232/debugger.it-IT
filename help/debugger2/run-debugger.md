---
description: nulle
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: 'null'
seo-title: Schermata Riepilogo
title: Schermata Riepilogo
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: b9147536b8312599dd3144cac31dea9f0f1c3625

---


# Schermata Riepilogo {#summary-screen}

Per eseguire Experience Cloud Debugger, fai clic sull’icona dell’estensione nella barra delle estensioni, quindi apri la pagina da esaminare in Chrome.

![](assets/start-icon.jpg)

Viene visualizzata la schermata Riepilogo di Adobe Experience Cloud Debugger.

![](assets/summary.jpg)

Questa schermata mostra una miniatura della pagina, nonché l’URL e il titolo di quest’ultima. Contiene, inoltre, informazioni su ciascuna soluzione Adobe Experience Cloud. Le informazioni visualizzate variano in base alla soluzione, ma in genere includono informazioni quali la libreria e la versione della soluzione (ad esempio, “AppMeasurement v2.9”) e gli identificatori dell’account (come l’ID suite di rapporti di Analytics, il codice client di Target, l’ID partner di Audience Manager e così via)

I numeri in blu accanto alle schede nella parte superiore della finestra mostrano il numero di chiamate server effettuate. You can reset these to zero by clicking **[!UICONTROL Clear All Requests]** within the respective tab.

Ad esempio, l’immagine seguente mostra informazioni su Adobe Target. Per esporre i dettagli dell’attività riportati di seguito senza autenticazione, devi implementare il listener di eventi Debugging nel codice o nel gestore di tag e devi attivare i [token di risposta](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) necessari nell’interfaccia utente di Target.

![](assets/summary-target2.jpg)

## Eseguire un audit in Auditor {#section-82bc57440406461ebf27a16855b71655}

Puoi utilizzare Adobe Auditor per eseguire una serie di controlli sulla pagina. To run Auditor, click **[!UICONTROL Auditor]** in the top menu, then click **[!UICONTROL Audit Page Now]**. Per aprire Adobe Auditor, fate clic su **[!UICONTROL Run Multi-Page Audit Now]**.

## Informazioni visualizzate nel debugger {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Debugger mostra le seguenti informazioni per ciascuna soluzione:

**Informazioni pagina**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Schermata della pagina </p> </td> 
   <td colname="col2"> <p>Miniatura della pagina </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>URL della pagina </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Titolo </p> </td> 
   <td colname="col2"> <p>Nome specificato nel tag <span class="codeph"> &lt;TITLE&gt;</span> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Suite di rapporti </p> </td> 
   <td colname="col2"> <p>Una <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external"> suite di rapporti</a> definisce il reporting indipendente e completo su un sito web scelto, su un insieme di siti web o su un sottoinsieme di pagine web </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versione </p> </td> 
   <td colname="col2"> <p>Versione <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> AppMeasurement</a> definita per la pagina </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versione visitatore </p> </td> 
   <td colname="col2"> <p>Versione della libreria <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> ID visitatore</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome pagina </p> </td> 
   <td colname="col2"> <p>Variabile <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> pageName</a> inviata ad Analytics che contiene un nome semplice del sito. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Moduli </p> </td> 
   <td colname="col2"> <p>Moduli caricati da Adobe Analytics </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partner </p> </td> 
   <td colname="col2"> <p>Il nome <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> del partner</a> per l’istanza DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versione </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"> Numero di versione</a> per l’istanza DIL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> ID utente univoco</a> associato all’istanza DIL </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nome </p> </td> 
   <td colname="col2"> <p>Nome della <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> proprietà</a> Adobe Launch </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versione </p> </td> 
   <td colname="col2"> <p>Versione di <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> Turbine</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Data build </p> </td> 
   <td colname="col2"> <p>Data build della <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> libreria</a> Launch </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ambiente </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"> Ambiente</a> utilizzato dalla libreria Launch </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Directory dello script </p> </td> 
   <td colname="col2"> <p>La directory in cui è memorizzato lo script Launch </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nome libreria </p> </td> 
   <td colname="col2"> <p>Nome della<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> libreria</a> Adobe DTM </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versione </p> </td> 
   <td colname="col2"> <p>Versione di Turbine </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Data build </p> </td> 
   <td colname="col2"> <p>Data build della <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> libreria</a> Launch </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ambiente </p> </td> 
   <td colname="col2"> <p>Ambiente utilizzato dalla libreria DTM </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Directory dello script </p> </td> 
   <td colname="col2"> <p>La directory in cui è memorizzato lo script DTM </p> </td> 
  </tr> 
 </tbody> 
</table>

**Servizio Adobe Experience Cloud ID**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>ID organizzazione Experience Cloud </p> </td> 
   <td colname="col2"> <p>Il tuo <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> Organization ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versione </p> </td> 
   <td colname="col2"> <p>Versione della libreria<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> ID visitatore</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Codice client </p> </td> 
   <td colname="col2"> <p>Il <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Codice client </a> di Target </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versione </p> </td> 
   <td colname="col2"> <p>La versione corrente di <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> o mbox.js </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome mbox globale </p> </td> 
   <td colname="col2"> <p>La<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> mbox</a> globale si riferisce alla singola chiamata server effettuata nella parte superiore di ogni pagina web nell’implementazione di Target </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome mbox </p> </td> 
   <td colname="col2"> <p>Il nome di una mbox intorno a una <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> posizione</a> sulla pagina. Disponibile senza autenticazione solo se implementi il listener di eventi Debugging nel codice o nel gestore di tag e attivi i <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> token di risposta necessari</a> nell’interfaccia utente di Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome attività </p> </td> 
   <td colname="col2"> <p>Il nome della <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> campagna o dell’attività</a> Target. Disponibile senza autenticazione solo se implementi il listener di eventi Debugging nel codice o nel gestore di tag e attivi i <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> token di risposta necessari</a> nell’interfaccia utente di Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Attività ID </p> </td> 
   <td colname="col2"> <p>ID dell’attività Target. Disponibile senza autenticazione solo se implementi il listener di eventi Debugging nel codice o nel gestore di tag e attivi i <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> token di risposta necessari</a> nell’interfaccia utente di Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nome ricetta </p> </td> 
   <td colname="col2"> <p>Il nome dell’ <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> esperienza</a> Target. Disponibile senza autenticazione solo se implementi il listener di eventi Debugging nel codice o nel gestore di tag e attivi i <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> token di risposta necessari</a> nell’interfaccia utente di Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID ricetta </p> </td> 
   <td colname="col2"> <p>ID della ricetta Target. Disponibile senza autenticazione solo se implementi il listener di eventi Debugging nel codice o nel gestore di tag e attivi i <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> token di risposta necessari</a> nell’interfaccia utente di Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Offerta </p> </td> 
   <td colname="col2"> <p>Nome dell’<a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external">offerta</a> Target. Disponibile senza autenticazione solo se implementi il listener di eventi Debugging nel codice o nel gestore di tag e attivi i <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> token di risposta necessari</a> nell’interfaccia utente di Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID offerta </p> </td> 
   <td colname="col2"> <p>ID dell’offerta Target. Disponibile senza autenticazione solo se implementi il listener di eventi Debugging nel codice o nel gestore di tag e attivi i <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> token di risposta necessari</a> nell’interfaccia utente di Target. </p> </td> 
  </tr> 
 </tbody> 
</table>

