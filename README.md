GCNGraph é rete che usa strato convoluzionale GCN (best modello in 'best_model_coloring.pth' ) 

SAGEGraph invece usa nei layer di convoluzione SAGE, per ora entrambi applicati ad un 5x5 ((best modello in 'SAGE_best_model_coloring_5x5_migliore.pth' ))


File e contenuto:

-SAGE_best_model_coloring_5x5_migliore.pth ha gli iperparametri giusti per colorare, infatti colora bene
-SAGE_best_model_coloring_7x7_ok.pth é ancora imperfetto(abbassando il lr da 0.02988 a 0.01 migliora la fluttuazione della loss)
-SAGE_best_model_coloring_7x7_migliore.pth per ora é quello con i parametri giusti
-
