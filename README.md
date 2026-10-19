# PolidoriFilippoContoCorrente

Progettazione Conto Corrente

Attributi:
nome: String //nome
cognome: String //cognome
contoCorrente: double //saldo nel conto corrente
cifraPrelievoVersamento: double //saldo da prelevare o versare
scelta: int //scegliere se prelevare - 1 o versare - 2
Metodi:
getNome(): String //restituisce il nome
getCognome():String //restituisce il cognome
getContoCorrente(): double //restituisce il valore del conto corrente
getScelta(): int //restituisce la scelta
getCifra(): double //restituisce il saldo da versare o da prelevare
controlloScelta(): double //controlla se la scelta è su prelevare o versare, continua con i calcoli e restituisce il saldo nel conto corrente dopo il versamento o il prelievo
toString(): String //restituisce una stampa di tutte le variabili
