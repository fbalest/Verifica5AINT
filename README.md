# Verifica di laboratorio Git e Docker

## Primo esercizio

1. Creare un repository Git in locale.
1. Effettuare *almeno* le seguenti **modifiche** (in una o più commit):
    1. Aggiungere un nuovo file *index.html* all'interno di una cartella *html*.
    1. Modificare il contenuto del file.
1. Creare un repository su GitHub e collegarlo a quello locale.
1. Allineare il repository remoto su GitHub con le modifiche effettuate.
1. **Consegnare su Classroom uno screenshot con i comandi eseguiti dalla bash e il repository locale.**

## Secondo esercizio

1. Creare una **copia locale** di questo repository .
1. Effettuare la seguente **modifica** al file *.css*:
    1. Modificare il colore di sfondo della pagina.
1. Creare un nuovo **branch** di lavoro ed effettuare le seguenti **modifiche** al file *.css* (in più commit):
    1. Modificare il colore di sfondo.
    1. Modificare la dimensione del paragrafo.
    1. Modificare l'allineamento del tag *H1*.
1. Riportare sul main le modifiche e risolvere eventuali conflitti.
1. **Consegnare su Classroom uno screenshot con i comandi eseguiti dalla bash.**

## Terzo esercizio

1. Creare un nuovo file *Dockerfile* nella cartella del repository creato nel **Primo esercizio**.
1. Scrivere un *Dockerfile* per creare un container che utilizzi un'immagine di base *nginx* e serva il contenuto della cartella *html* contenente il file *index.html*.
1. Costruire l'*immagine* Docker.
1. Eseguire il *container*.
1. Aprire il browser e verificare che il contenuto di *index.html* sia visibile all'indirizzo *http://localhost:2080*.
1. **Consegnare su Classroom uno screenshot con i comandi eseguiti e il risultato nel browser.**
