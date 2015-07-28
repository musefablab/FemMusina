# FemMusina
G.Toller, M.Perini, N.Orandini, G.Berti  Fem Musina: una macchina governata da Arduino per l’irrigazione di piante in vaso  Il MUSE FabLab, laboratorio di fabbricazione digitale del Museo delle Scienze di Trento, con la collaborazione della Fondazione Edmund Mach  ha realizzato un prototipo di  macchina per l’irrigazione di piante in vaso. Ogni vaso è dotato di un sensore dell’umidità del suolo e di una propria linea irrigua. Il sistema, governato da un hardware e da un software creati a partire dalla piattaforma informatica Arduino, dosa l’acqua in modo adeguato alle esigenze di ogni pianta. Molti pezzi speciali del prototipo, ad esclusione di quelli che richiedevano tornitura, sono stati realizzati con gli strumenti in dotazione al FabLab: taglio laser, stampante 3D, fresatrice.  Nella progettazione si è puntato ad abbassare i costi riducendo al massimo il numero di elettrovalvole. Nella versione attuale, basata su un distributore rotante, una sola elettrovalvola può alimentare 16 linee, ma è previsto di espanderne il numero. Il controller scansiona periodicamente i sensori di umidità nei vasi e, in base alla risposta, dosa la quantità d’acqua somministrata a ciascuna pianta. Situazioni eccezionali quali ad esempio mancanza d’acqua o mancanza di reazione all’irrigazione da parte dei sensori, vengono gestite da apposite routine di calcolo che generano segnali di allarme.   