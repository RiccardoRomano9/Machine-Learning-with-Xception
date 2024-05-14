# Riconoscimento di Condizioni Meteorologiche e di Illuminazione nelle Ferrovie Utilizzando la Rete Neurale Xception

Questo repository contiene un progetto di Intelligenza Artificiale per il riconoscimento accurato di cinque diverse condizioni meteorologiche e di illuminazione nelle ferrovie, al fine di migliorare l'affidabilità e la sicurezza dei sistemi ferroviari autonomi.

## Problema

Le ferrovie, come mezzo di trasporto ecologico, affrontano sfide legate alle condizioni meteorologiche e di illuminazione variabili, che possono compromettere la capacità dei sistemi di guida autonoma di riconoscere e reagire con precisione a diverse situazioni. L'obiettivo è sviluppare un modello di Intelligenza Artificiale in grado di identificare accuratamente le seguenti condizioni:

- Bright Light
- Darkness
- Rainy
- Sun Flare (Interferenze dirette da luce solare)
- Shadows

Inoltre, è presente una categoria 'Clean' per le condizioni normali.

## Metrica di Valutazione

L'Accuracy è la metrica utilizzata per valutare l'accuratezza del modello nel riconoscere le diverse condizioni meteorologiche e di illuminazione.

## Rete Neurale Utilizzata: Xception

Xception è un tipo di architettura di rete neurale convoluzionale (CNN) sviluppata da François Chollet di Google AI nel 2017. Derivata dall'architettura Inception, Xception implementa un concetto di separazione delle convoluzioni per ridurre il numero di parametri e migliorare l'efficienza computazionale della rete.

Xception è stata addestrata su un'ampia varietà di immagini provenienti da dataset standard di visione artificiale, come ImageNet, e beneficia di un addestramento su dataset diversificati per generalizzare meglio a una vasta gamma di immagini del mondo reale.

## Obiettivo

Il modello Xception è progettato per estrarre caratteristiche da immagini in modo efficiente e preciso, utilizzando una struttura che massimizza la profondità senza aumentare eccessivamente il numero di parametri. Questo lo rende una scelta popolare in applicazioni di visione artificiale, incluso il riconoscimento di condizioni meteorologiche e di illuminazione nelle ferrovie.

