
# Traccia 4 - Prova all'impronta Programmazione I #

Sviluppare una function C che, dati come parametri di input un array 2D di double, il numero delle righe e il numero delle colonne, determina e restituisce come parametro di output il massimo tra le somme degli elementi di ogni colonna.

# Soluzione spiegata #

immaginiamo di avere la seguente matrice: 

| 00 | 01 | 02 | 03 |

| 10 | 11 | 12 | 13 |

| 20 | 21 | 22 | 23 |               

| 30 | 31 | 32 | 33 |

| 40 | 41 | 42 | 43 |

| 50 | 51 | 52 | 53 |

##### Quindi una 6 x 4 #####

Possiamo notare che mentre il numero riga cambia ogni volta che ci spostiamo in altezza, il numero colonna rimane uguale, quindi, per sommare gli elementi di una colonna basterà iterare la matrice seguendo le regole precedenti, come da codice.
