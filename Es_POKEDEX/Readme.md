### Pokedex

ATT: quando carico la pagina deve esserci un form nel quale si chiede all'utente il suo nome. 

Utilizzando l' API dei pokemon stampa una lista casuale di pokemon
https://pokeapi.co/api/v2/pokemon/?limit=20&offset=0

Accanto ad ogni pokemon ci sarà un pulsante "Inserisci nel Pokedex" con un massimo di 3 pokemon iniziali.
Raggiunti i 3 pokemon non ne posso più inserire altri.

In alto nella navbar ci sarà la voce di menu "Pokedex", questa voce ti trasferirà sulla pagina pokedex.html nella quale verranno mostrati i 3 pokemon scelti. 

Per ogni pokemon scelto dovrà esserci la possibilità di modificare le info
es: Pikachu
tipo: elettrico
desc: da abbinare a contatori autorizzati

al click sul pulsante modifica posso aggiungere altre info tramite form (nella card dovrà esserci la voce localizza, al click compare una mappa con il segnalino della posizione del pokemon, alla comparsa della mappa comparirà un'altra voce "controlla meteo nella località"
al click comparirà una finestra nella quale verrà mostrato il meteo attuale (temp, icona, umidità ecc))

inserendo :
nickname: Alfredo
geolocalizzazione: via dei matti n0 roma(cliccando sull'indirizzo apro la mappa e mi porta lì)


USARE BS 5.3

Pagina Home:
Usare un list-group di bs5 per mostrare i pokemon.
All'inserimento far comparire un avviso in un alert di bs5 (dismissable) con posizione absolute in basso a destra dello schermo.

Pokedex:
Usare le card di bs5
