# DAA_Generator

Un semplice file excel che permette la creazione automatica di DAA doganali a partire dal file XML scaricato dal sito della dogana.

V3.0 Features

- UserForm per la selezione di malti o birre
- Pulsante salve per duplicare il foglio con valori solo valore e pulsanti interattivi eliminati
- Lista degli indirizzi più frequenti per l'invio di birre
- Import di DAA in entrata con Malti Anker (riconoscimento automatico della referenza se presente nel databaseMalti. Questo ogni tanto va aggiornato aggiungendo nuove referenze aggiunte nei nuovi listini)
- Import di DAA in entrata con Malti vari (le celle con @@ vanno inserite a mano)
- Import di DAA in uscita con Malti vari (le celle con @@ vanno inserite a mano)
- Import di DAA in entrata/uscita con Birre
  -Se l'import genera errore in qualche celle significa che la birra non è riconosciuta. Va perciò aggiunta nel database delle birre specificando la quantità di unità per cassa e la capacità di ogni unità
  
BUGS TO FIX
- Alcune referenze (poche) del listino Anker hanno la capacità indicata in ML invece che in LT. Tali quantità andrebbero convertite o possono provocare degli errore nel DAA.
- Aggiungere il caso in cui la spedizione sia di vini.
- Aggiungere la gestione dell'errore che si genera quando si prova a salvare un secondo DAA con la stessa destinazione e quindi con lo stesso sheet name
