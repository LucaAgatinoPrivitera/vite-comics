:pacco: CONSEGNA
Continuate a lavorare nella stessa repo di ieri. Oggi però andiamo a popolare il main content.

:roccia: MILESTONE 1
Create un componente che in base ad un array (in allegato) vada a generare delle card in pagina.
Sarà il macro componente che contiene tutti i fumetti, qualcosa come ComicsList.vue.
Dovrete copiare l'array allegato nel vostro data e iterare con un v-for.

:roccia: MILESTONE 2
Ora provate a creare un componente figlio che rappresenti la singola card, del tipo SingleComic.vue.
Fate in modo che accetti un dato in ingresso (usando le props).
Dal componente padre (es. ComicsList) modificate il ciclo in modo che richiami questo nuovo componente e gli passi il fumetto in questione tramite props.