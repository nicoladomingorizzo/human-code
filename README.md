# human-code

Aprire un pacchetto di figurine
Ce l’ho, mi manca!
Che emozione, ogni volta che apro un pacchetto nuovo... chissà se troverò quella figurina così rara!
Dopo averle sfilate dal pacchetto, me le passo tra le mani controllando nell’album: attacco subito quelle nuove, mentre le doppie le metto in un mazzetto a parte. Ormai ne sto accumulando diverse, spero di riuscire a combinare diversi scambi sabato con i miei amici! 

<!-- Preparazione postazione sbusto -->

Prendiamo l'album delle figurine dallo scaffale

Posizioniamo l'album sul tavolo

Prendiamo un pacchetto di figurine

Ci posizioniamo seduti sulla sedia

<!-- /Preparazione postazione sbusto -->

<!-- Apertura pacchetto -->

Apriamo il pacchetto

Usciamo le figurine dal pacchetto

Osserviamo il numero di una figurina

?SE controllando il numero notiamo che è una fuoriserie
    -La inseriamo all'interno di una sleeve protettiva
:ALTRIMENTI
    ?SE la figurina non è presente all'interno dell'album
        -La attacchiamo nello spazio prefefinito
    : ALTRIMENTI
        -La mettiamo nel mazzo dei doppioni

[Ciclo finché non finisci le figurine all'interno del pacchetto]

Prendiamo l'album delle figurine

Posiamo l'album delle figurine sullo scaffale

<!-- /Apertura pacchetto -->

<!-- Scambio con gli amici -->

Aspettiamo che sia sabato

Prendiamo l'album dallo scaffale

Prendiamo il mazzo dei doppioni

Andiamo a casa di Fabrizio

Arrivano a casa di Fabrizio anche altri due amici (Angelo, Simone e Matteo)

Osserviamo il numero di una figurina del mazzo dei doppioni di Angelo

?SE la figurina è presente all'interno del mio album
    -Andiamo alla successiva 
: ALTRIMENTI
    -Angelo controlla il mio mazzo di doppioni
            ? SE Angelo trova il numero della figurina che gli manca
                -Facciamo lo scambio
                -Ripeti riga 45
            : ALTRIMENTI
                -Non facciamo scambi con Angelo

Osserviamo il numero di una figurina del mazzo dei doppioni di Simone

?SE la figurina è presente all'interno del mio album
    -Andiamo alla successiva 
: ALTRIMENTI
    -Simone controlla il mio mazzo di doppioni
            ? SE Simone trova il numero della figurina che gli manca
                -Facciamo lo scambio
                -Ripeti riga 57
            : ALTRIMENTI
                -Non facciamo scambi con Simone

Osserviamo il numero di una figurina del mazzo dei doppioni di Matteo

?SE la figurina è presente all'interno del mio album
    -Andiamo alla successiva 
: ALTRIMENTI 
    -Simone controlla il mio mazzo di doppioni
            ? SE Matteo trova il numero della figurina che gli manca
                -Facciamo lo scambio
                -Ripeti riga 69
            ALTRIMENTI :
                -Non facciamo scambi con Matteo

<!-- /Scambio con gli amici -->







