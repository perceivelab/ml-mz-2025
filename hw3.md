---
layout: page
---

## Homework 3

Questo homework ha l'obiettivo di affrontare un problema di classificazione su un dataset affetto da rumore nel training set che può portare a overfit. La soluzione deve essere basata sull'uso di reti neurali. 
Il dataset da utilizzare è una variante di CIFAR10, che può essere inclusa in Kaggle attraverso questo link:
[https://www.kaggle.com/datasets/alessiomasano/cifar10-hw3](https://www.kaggle.com/datasets/alessiomasano/cifar10-hw3).

Nello specifico, i requisiti dell'homework sono:
* caricare correttamente il dataset;
* utilizzare MLP;
* adottare opportuni accorgimenti per evitare l'overfit;
* effettuare opportunamente la model selection;
* riportare le prestazioni ottenute, secondo le metriche di valutazione appropriate.

La strategia di esecuzione di ciascuna di queste fasi è a scelta dello studente. La valutazione dell'homework terrà conto della correttezza metodologica, della correttezza dell'implementazione e della completezza dell'approccio di ricerca del modello migliore.

Nel caso in cui l'allenamento dei modelli risulti eccessivamente dispensioso in termini di tempo, è possibile valutare l'ipotesi di sotto-campionamento del dataset.

### Consegna

La consegna del MHW dovrà essere effettuata su GitHub, in un repository chiamato **esattamente** `hw3`, e dovrà includere:
* il notebook contenente la soluzione;
* una presentazione in PowerPoint, da esporre in sede di esame, che includa:
  * descrizione del dataset;
  * descrizione della metodologia adottata;
  * descrizione dei risultati. 