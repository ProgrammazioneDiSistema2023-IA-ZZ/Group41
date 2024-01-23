# Group41
Questo progetto è stato sviluppato dal gruppo 41, composto da:
- Nicolò Marsicano
- Ernesta Maria Sichetti
- Luca Romeo

Tale progetto si pone l'obiettivo di analizzare un sistema operativo differente rispetto ad OS161 e aggiungere una serie di funzionalità scaturite dalla conoscenza pregressa fornitaci dai laboratori svolti durante il corso di Programmazione di Sistema.
Nel nostro caso la selezione è ricaduta su xv6, un sistema operativo didattico Unix-like basato su Unix V6, creato nel 2006 a scopo educativo dal Massachusetts Institute of Technology.

Le aggiunte inserite all'interno di xv6 riguardano:
-  un sistema di classificazione dei processi in base ad un livello di priorità.
- la gestione e la modifica di tali priorità da parte dell'utente.
- la possibilità, da parte dell'utente, di cambiare la modalità di scheduling dei processi.
### Come eseguire il setup di xv6
- Eseguire il pull di questo repository sulla propria macchina locale
- Posizionarsi, da terminale, nella cartella `xv6-public` lanciare `wsl --install`
- Una volta dentro WSL, posizionarsi all'interno del repository `xv6-public` e lanciare il comando `make qemu-nox` per visualizzare il menù
