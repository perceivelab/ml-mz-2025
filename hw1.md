---
layout: page
---

## Homework 1

In questo homework, estenderete il codice scritto durante l'esercitazione sulla regressione lineare, al fine di implementare un meccanismo di model selection, analizzando le prestazioni ottenute da diverse combinazione di iperparametri. 

Nello specifico, i requisiti dell'homework sono:
* scrivere la funzione `pipeline()`, che riceve un training set, un validation/test set e un insieme di iperparametri, e allena un modello di regressione lineare. In particolare, la funzione deve:
  * se richiesto, applicare la PCA, utilizzando un numero specifico di componenti (passato come iperparametro) e opzionalmente standardizzando i dati;
  * se richiesto, applicare la standardizzazione dei dati (a prescindere che questa sia stata o meno fatta durante la PCA);
  * se richiesto, applicare la regolarizzazione;
  * allenare il modello di regressione lineare;
  * calcolare MAE per training set e validation/test set;
* dividere il dataset in training set, validation set e test set;
* tramite `pipeline()`, valutare tutte le configurazioni possibili di iperparametri, e selezionare quella che ottiene le migliori prestazioni sul validation set;
  * considerate che ciascun allenamento può modificare i dati (ad esempio, tramite standardizzazione); pertanto, ogni volta che allenate un modello dovreste sempre lavorare su [una nuova copia dei dati](https://numpy.org/doc/2.2/reference/generated/numpy.ndarray.copy.html);
* valutare le prestazioni del modello selezionato sul test set;
* visualizzare:
  * la migliore configurazione;
  * il miglior MAE sul validation set;
  * il MAE corrispondente sul training set;
  * il MAE corrispondente sul test set. 

Il codice fornito per lo svolgimento dell'homework deve essere utilizzato nella soluzione, e **non va modificato il alcun modo**.

### Consegna

La consegna del MHW dovrà essere effettuata su GitHub, in un repository chiamato **esattamente** `hw1`, e dovrà includere il notebook contenente la soluzione. 