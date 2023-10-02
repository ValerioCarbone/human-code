# Posizionamento
- Prendere la pratica
- Arrivare allo scanner
- SE lo scanner è occupato ALLORA attendere che sia libero:
  - SE lo scanner rimane occupato per troppi minuti ALLORA procedere con altre tasks e ritentare più tardi
  - SE lo scanner si libera in pochi minuti ALLORA procedere alla scannerizzazione 
- SE lo scanner è libero procedere con la scannerizzazione
# Scannerizzazione
- Prendere il primo foglio e scannerizzare la pagina che ha il numero minore OPPURE viene prima tra le due
- SE la macchina ha terminato la scannerizzazione del foglio ALLORA girare la pagina
- ALTRIMENTI attendo la fine della scannerizzazione
- SE la pagina è vuota ALLORA controllare che la pila dei fogli non ancora scannerizzati abbia almeno un foglio:
    - SE la pila è terminata ALLORA concludere la scannerizzazione
    - ALTRIMENTI ripetere le azioni delle sezione "Scannerizzazione" 
- ALTRIMENTI procedere alla scannerizzazione 
- Riporre il foglio su una superficie con la pagina che ha il numero minore OPPURE viene prima tra le due rivolta verso il basso
- Ripetere le azioni della sezione "Scannerizzazione" FINCHÉ ho terminato di scannerizzare tutti i fogli E ogni lato di questi con del contenuto