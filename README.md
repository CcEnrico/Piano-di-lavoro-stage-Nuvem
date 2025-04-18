# Piano di Lavoro – Enrico Cotti Cottini

Questa repository contiene il Piano di Lavoro per il mio tirocinio curricolare presso **Nuvem Srl**, redatto utilizzando il [Template Piano di Lavoro Stage](https://github.com/FIUP/Template-piano-di-lavoro-stage) sviluppato per il corso di laurea in Informatica dell'Università di Padova.

📄 **[Scarica il PDF del Piano di Lavoro](./PianoDiLavoro_ECC_Nuvem.pdf)**

---

## Struttura del template

Il template è diviso in sezioni, secondo la seguente struttura:

> ⚠️ In caso non si vogliano utilizzare alcune sezioni, è sufficiente commentarle nel file `PianoDiLavoro.tex`.

1. **Preface**: definisce il frontespizio del Piano di Lavoro, non necessita di modifiche (prende i dati da `Dati.tex`);
2. **Contatti**: include la sezione di contatti, non necessita di modifiche;
3. **ScopoStage**: da personalizzare con una breve descrizione dello stage e dei compiti che lo studente svolgerà;
4. **InterazioneStudenteTutor**: da personalizzare specificando modalità e frequenza dell’interazione tra studente e tutor aziendale;
5. **ProdottiAttesi**: da compilare con la lista di prodotti software e documentali che lo studente dovrà realizzare, con nome e descrizione per ciascuno;
6. **ContenutiFormativi**: da descrivere indicando le tecnologie e le conoscenze che si prevede di approfondire;
7. **PianificazioneLavoro**: da personalizzare con:
   - un elenco delle attività settimanali;
   - una tabella che riassuma la ripartizione oraria;
8. **Obiettivi**: include gli obiettivi obbligatori, desiderabili e facoltativi; non necessita di modifiche (prende i dati da `Dati.tex`);
9. **Diagramma**: mostra un diagramma di Gantt con la pianificazione iniziale delle attività.

   > L'immagine è caricata da `img/gantt.png`. Per modificarla basta sovrascrivere l'immagine con un'altra dallo stesso nome.

10. **Approvazione**: sezione per la firma di tutor aziendale, tutor universitario e studente, con spazio per eventuale timbro aziendale.

> ℹ️ Le sezioni **5**, **9** e **10** non sono sempre richieste, ma potrebbero essere richieste dal tutor interno.

---

## Scelta dello stile

Il template prevede due modalità di impaginazione, selezionabili nel file `Layout.tex`:

1. **Stile Unipd**  
   Header: logo UNIPD, nome e matricola dello studente, azienda.  
   Footer: numero pagina (in basso a destra).

2. **Stile Aziendale**  
   Header: logo aziendale, nome azienda, sito.  
   Footer: contatti aziendali completi ai lati, numero pagina centrato.

### Come usare lo stile aziendale

1. Chiedere l’autorizzazione all’azienda per l’uso di logo e dati.
2. Inserire nella cartella `img` un file chiamato `logo_azienda.png`.
3. Nel file `Layout.tex`:
   - commentare `\stileUNIPD`
   - decommentare `\stileAziendale`

---

## ⚠️ Attenzione

Questo template genera un file `.pdf` utile per la revisione e approvazione del piano di lavoro. Tuttavia, alcuni docenti potrebbero richiedere una stampa su carta intestata dell'azienda. Assicurati di verificare con il tuo tutor interno prima della consegna ufficiale.

---

## Crediti

- Template originale di Michele Caovilla (Mich)
- Rivisitazione completa del template: Riccardo Montagnin
- Modifiche aggiuntive: Federico Silvio Busetto
- Personalizzazione per questo progetto: **Enrico Cotti Cottini**
