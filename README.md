GCNGraph é rete che usa strato convoluzionale GCN (best modello in 'best_model_coloring.pth' ) 

SAGEGraph invece usa nei layer di convoluzione SAGE, per ora entrambi applicati ad un 5x5 ((best modello in 'SAGE_best_model_coloring_5x5_migliore.pth' ))


File e contenuto:

-SAGE_best_model_coloring_5x5_migliore.pth ha gli iperparametri giusti per colorare, infatti colora bene

-SAGE_best_model_coloring_7x7_ok.pth é ancora imperfetto(abbassando il lr da 0.02988 a 0.01 migliora la fluttuazione della loss)

-SAGE_best_model_coloring_7x7_giustiPARAM.pth per ora é quello con i parametri giusti ma non funge

-6x6 é quasi giusto, mancano tipo 1/2 link

-8_12 é il primo dove coloro i link di rosso sbagliati

-9x9 é il primo in cui mi sono accorta che se aumentano i colori devo aumentarli anche quando faccio la mappa, senno non vedo i pallini, ma solo i link rossi
