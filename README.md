### Obiettivi

Il progetto **deblur** prevede la costruzione di una serie di modelli il cui scopo è quello di riuscire, partendo da un immagine corotta da **rumore** e **sfocamento Gaussiano,** a ricostruire l'immagine originale. Il progetto prevede l'analisi dei metodi usati e dei loro risultati a fronte di diversi problemi test.

### Image deblurring

Tutti i metodi usati sono riformulazioni del problema dei **minimi quadrati,** questo è quindi una funzione da minimizzare e viene naturale l'utilizzo dei metodi di ottimizzazione in particolare del **Gradient descent.** Non dobbiamo aspettarci però che questi metodi siano infallibili anzi lo sono eccome ed in base al problema test possiamo avere risultati più o meno soddisfacenti. 

Nel corso delle nostre prove verificheremo come i nostri metodi siano particolarmente sensibili al rumore infatti non ci aspettiamo in alcun modo di poterlo diminuire ed anzi vedremo come questo possa compromettere la nostra ricostruzione. ****Non dimentichiamoci inoltre problemi come la non unicità del minimo.
