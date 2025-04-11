---
layout: page
---

## Homework 2

Questo homework ha l'obiettivo di affrontare un problema di classificazione, cercando di ottenere le migliori prestazioni possibili, utilizzando i modelli e le metodologie viste a lezione.
Il dataset da utilizzare è **CIFAR10**: contiene 60,000 immagini (50,000 di training e 10,000 di test) divise in 10 classi, a risoluzione 32x32 pixel, a colori. [Questa](https://www.cs.toronto.edu/~kriz/cifar.html) è la pagina di riferimento del dataset.

Nello specifico, i requisiti dell'homework sono:
* caricare correttamente il dataset CIFAR10;
* utilizzare i seguenti modelli di classificazione: regressione logistica, k-NN, SVM, decision tree;
* effettuare opportunamente la model selection;
* riportare le prestazioni ottenuti, secondo le metriche di valutazione appropriate.

La strategia di esecuzione di ciascuna di queste fasi è a scelta dello studente. La valutazione dell'homework terrà conto della correttezza metodologica, della correttezza dell'implementazione e della completezza dell'approccio di ricerca del modello migliore.

Nel caso in cui l'allenamento dei modelli risulti eccessivamente dispensioso in termini di tempo, è possibile valutare l'ipotesi di sotto-campionamento del dataset.

### Consegna

La consegna del MHW dovrà essere effettuata su GitHub, in un repository chiamato **esattamente** `hw2`, e dovrà includere:
* il notebook contenente la soluzione;
* una presentazione in PowerPoint, da esporre in sede di esame, che includa:
  * descrizione del dataset;
  * descrizione della metodologia adottata;
  * descrizione dei risultati. 