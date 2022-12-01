# Modelli matematici e pandemia

La pandemia continua ad esercitare il suo ruolo di ospite indesiderato rendendo prolematica la vita sul pianeta Terra. La ricerca scientifica si è attivata e ha condotto a risultati utili anche se non ancora risolutivi. In questo contesto si è anche cercato di coordinare azioni preventive e curative a livello di nazioni. Infatti, i numeri in gioco, l’impatto sulle strutture sanitarie e sui sistemi di produzione sono tali da richiedere un impegno particolarmente intenso.

Seguendo il modello di dialogo scientifico proposto indichiamo le ipotesi che hanno condotto ai modelli proposti in [\[2, 4, 5\]](riferimenti-bibliografici.md):

1. La derivazione del modello richiede un approccio multiscala ove la scala macroscopica corrisponde agli individui che possono essere infettati da dinamiche alla scala microscopica delle particelle del virus. Successivamente la dinamica all’interno del soggetto infettato si sviluppa alla scala microscopica coninvolgendo particelle del virus e gli agenti del sistema immunitario.
2. L’entità del contagio non è una quantità generica, ma depende dal livello dell’infezione, quindi da quella che viene definita `carica virale` ed è una conseguenza di quella che viene definita `distanza sociale` fra individui.
3. La competizione fra il virus proliferativo e il sistema immunitario ha luogo negli organi infettati, prevalentemente nei polmoni, con possibile progressione (regressione) del livello di infezione. La dinamica si conclude con guarigione o decesso.
4. Il virus, nella fase di proliferazione, può mutare generando varianti che se meno adatte all’ambiente vengono soppresse dal sistema immunitario, o si affermano se più idonee all’ambiente. Si tratta di una dinamica post-Darwiniana con probabilità di mutazioni che cresce al crescere del livello globale di infezione nella popolazione.
5. Programmi di vaccinazione possono sono sviluppati per incrementare la capacità di difesa del sistema immunitario. Si tratta di una azione che va programmata anche tenendo conto della resistenza soggettiva di una parte della popolazione a sottoporsi alla vaccinazione. I vaccinati possono comunque infettarsi sebbene con livelli di carica virale decisamente inferiore a quella dei soggetti che non lo sono.

La dinamica descritta al punto 3 è visualizzata nella figura 4. Da queste ipotesi si comprende che il sistema immunitario ha un ruolo chiave. Questa capacità difensiva non è dello stesso livello per tutti gli individui. Infatti, il livello di questa dipende non solo dall’età, ma anche da vari fattori, per esempio la condotta di vita e l’alimentazione. Inoltre, cure antivirali possono indebolire l’azione del virus e quindi, rendere più efficace la risposta immunitaria. Questi temi il lettore interessato a una bibliografia sul tema, può riferirsi a [\[6, 7\]](riferimenti-bibliografici.md).

A partire dalle ipotesi 1–5 si deriva il modello matematico proposto in [\[2, 4, 5\]](riferimenti-bibliografici.md). Questo descrive la dinamica nel tempo delle densità numeriche dei seguenti soggetti: Individui infettati sia lal virus originale e sia anche a causa delle varianti; Ricoveri ospedalieri per crescenti livelli di terapia; Decessi e guarigioni. Il termine densità indica che il numero di soggetti è riferito al numero iniziale di individui nella zona studiata.

Inoltre, il modello descrive come processi di vaccinazione influenzano le dinamiche di infezione, ospedalizzazione, guarigione etc. Lo studio richiede sia un ben definito il programma di vaccinazione nel senso di numeri di vaccinati nel tempo anche in relazione al numero di soggetti coinvolgibili e delle relative tipologie di fragilità ovvero ruolo operativo (lavoro) nella società.

![Figura 2 - Alto: Dinamica dell’azione del sistema immunitario; Basso: Azione del virus.](<../.gitbook/assets/Schermata 2022-01-23 alle 12.46.50.png>)

Alcuni esempi, fre i molti possibili, sono indicati nel seguito riferendosi alle dinamiche di due onde successive, ove la prima onda è controllata mendiante azioni che impongono distanziamento, mentre la seconda nasce per l’allentamento del distanziamento. La coordinata verticale riporta le densità della popolazione infetta e la coordinata orizzontale il tempo. Questo è riferito all’intervallo di tempo della prima onda fino al distanziamento che genera la seconda onda. Nelle prime tre figure si studia la dinamica prima nel caso di virus primario e successivamente nel caso con presenza di di una variante. L’interpretazione dei risultati, in corsivo-grassetto, segue queste simulazioni proposte a titolo di esempio.

È utile precisare meglio il significato di distanziamento: si intende l’insieme di azioni, generalmente indotte da normative, che riducono, o proteggono, il contatto fisico fra persone (mascherine, etc.). Questa entità fisica-sociale misura sia la probabilità di contatto e sia l’entità dell’infezione iniziale carico virale iniziale. Nei modelli matematici il distanziamento è misurato da un parametro con valori da 0 a 1, che corrispondono, rispettivamente, a chiusura totale e apertura senza alcuna limitazione.

Queste simulazioni, ed il complesso di quelle che sono state prodotte dal Team di lavoro [\[2, 4\]](riferimenti-bibliografici.md), conduce alle seguenti indicazioni:&#x20;

![Figura 3. Densità di infetti nel tempo per diversi indici (bassi) di confinamento.](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.03.png>)

![Figura 4. Densità di infetti nel tempo per diversi indici (elevati) di confinamento.](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.14.png>)

![Figura 5. Densità di infetti nel tempo: da virus primario (blu) e da variante (arancione).](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.20.png>)

* _**Anche dopo un elevato distanziamento, il vurus continua a circolare e riprende vigore infettivo nell'onda successiva. Non appena il distanziamento è allentato. La seconda onda risulta tando più dannosa quanto maggiore è la riduzione di questo**_.
* _**La variante è di norma più aggressiva del virus primario e finisce con predominare, soprattutto nella seconda onda. La riduazione del distanziamento contribuisce al predominio della variante.**_

A partire da queste simulazioni osserviamo i possibili effetti di un programma di vaccinazione nelle due figure successive. La figura 6, è la simulazione base in assenza di processo di vaccinazione, la figura 7 visualizza il ruolo di un processo di vaccinazione che coorrisponde ad una attivazione del sistema immunitario.

![Figura 6. Densità di infetti nel tempo da virus primario e variante.](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.27.png>)

![Figura 7. Densità di infetti nel tempo, da virus primario, variante e vaccinati.](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.34.png>)

Il complesso delle simulazioni [\[2, 4\]](riferimenti-bibliografici.md) conduce alle seguenti indicazioni:

* _**Un piano di vaccinazione continuo riduce di molto, soprattutto nella seconda onda, il numero degli infetti. Tuttavia, non annulla la circolazione del virus. Questo riprenderà nel momento in cui il distanziamento è rilassato (o peggio annullato).**_
* _**Un piano di vaccinazione non elimina il predominio della variante. Il modello indica come sia possibile anche il contagio dei vaccinati. Questi tuttavia richiedono livelli inferiori di terapia. Inoltre, il modello indica come la circolazione del virus porta all'infezione dei vaccinati quantitativamente più intensa quanto più circola l'infezione del virus.**_
