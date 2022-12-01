# Modelli matematici e pandemia

La pandemia continua a esercitare il suo ruolo di ospite indesiderato rendendo problematica la vita sul pianeta Terra. La ricerca scientifica si è attivata e ha condotto a risultati utili anche se non ancora risolutivi. In questo contesto si è anche cercato di coordinare azioni preventive e curative a livello di nazioni. Infatti, i numeri in gioco, l’impatto sulle strutture sanitarie e sui sistemi di produzione sono tali da richiedere un impegno particolarmente intenso. Seguendo il modello di dialogo scientifico proposto nella [sezione precedente](quale-dialogo-fra-matematica-scienze-naturali-e-sociali.md), indichiamo le ipotesi che hanno condotto ai modelli proposti in [\[2, 4, 5\]](riferimenti-bibliografici.md):

1. La _derivazione del modello matematico_ richiede un approccio multiscala ove la scala macroscopica corrisponde agli individui che possono essere infettati da dinamiche alla scala microscopica delle particelle del virus. Successivamente la dinamica all’interno del soggetto infettato si sviluppa alla scala microscopica coinvolgendo particelle del virus e gli agenti delsistema immunitario.
2. L’`entità del contagio` non è una quantità generica, ma dipende dal livello dell’infezione, quindi da quella che viene definita `carica virale` __ ed è una conseguenza di quella che viene definita `distanza sociale` __ fra individui.
3. La competizione fra il virus con abilità di proliferare all’interno di cellule infettate e il sistema immunitario __ ha luogo negli organi infettati, prima nelle vie respiratorie e successivamente nei polmoni, con possibile progressione (regressione) del livello di infezione. La dinamica si conclude con guarigione o decesso.
4. Quando la cellula infettata contribuisce alla proliferazione del virus liberando migliaia di copie, commette errori generando varianti che se meno adatte all’ambiente vengono soppresse dal sistema immunitario, o che si affermano se più idonee all’ambiente. Questa selezione può essere interpretata come una dinamica post darwiniana con probabilità dimutazioni che cresce al crescere del livello globale di infezione nella popolazione.
5. Programmi di vaccinazione __ possono sono sviluppati per incrementare la capacità di difesa del sistema immunitario. Si trattadi una azione che va programmata anche tenendo conto della resistenza soggettiva di una parte della popolazione a sottoporsi alla vaccinazione. I vaccinati possono comunque infettarsi, comunque con livelli di carica virale decisamente inferiore a quella dei soggetti che non lo sono.

Dalle  **ipotesi  1–5** si   comprende che il sistema immunitario ha un ruolo chiave. Questa capacità difensiva non è dello stesso livello per tutti gli individui. Infatti, il livello di questa dipende non solo dall’età, ma anche da vari fattori, per esempio la condotta di vita e l’alimentazione. Inoltre, cure antivirali possono indebolire l’azione del virus e quindi rendere più efficace la risposta immunitaria. Il lettore interessato a una bibliografia sul tema, può riferirsi a [\[7, 8, 12\]](riferimenti-bibliografici.md).

<div>

<figure><img src="../.gitbook/assets/Screenshot 2022-12-01 alle 14.57.25 copia.png" alt=""><figcaption><p>​​Figura 2a. Dinamica dell’azione del sistema immunitario<br></p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/Screenshot 2022-12-01 alle 14.57.25 (1).png" alt=""><figcaption><p>​​Figura 2b. Azione del virus.<br></p></figcaption></figure>

</div>

A partire dalle **ipotesi 1–5** si deriva il modello matematico proposto in [\[2, 4, 5\]](riferimenti-bibliografici.md). Il modello descrive la dinamica nel tempo delle densità numeriche dei seguenti soggetti:&#x20;

* individui infettati sia dal virus originale e sia anche a causa delle varianti;
* ricoveri ospedalieri per crescenti livelli di terapia;
* decessi e guarigioni.

Il termine `densità` __ indica che il numero disoggetti è  riferito al numero iniziale di individui nella zona studiata. Inoltre, descrive come i processi di vaccinazione influenzano le dinamiche di infezione, ospedalizzazione, guarigione etc. Lo studio richiede sia un ben definito programma di vaccinazione nel senso di numeri di vaccinati nel tempo anche in relazione al numero di soggetti coinvolgibili e delle relative tipologie di fragilità, ovvero il ruolo operativo (lavoro) nella società.

Alcuni esempi, fra i molti possibili, sono indicati nel seguito riferendosi alle dinamiche di due onde successive, ove la prima onda è controllata mediante azioni che impongono distanziamento, mentre la seconda nasce per l’allentamento del distanziamento. La coordinata verticale riporta le densità della popolazione infetta e la coordinata orizzontale il tempo. Questo è riferito all’intervallo di tempo della prima onda fino al distanziamento che genera la seconda onda.&#x20;

Nelle **prime tre figure** si studia la dinamica prima nel caso di virus primario e nelle **successive due** nel caso con presenza di una variante.&#x20;

L’interpretazione dei risultati, segue queste simulazioni, proposte a titolo di esempio. In dettaglio:

La figura 3 visualizza il ruolo della riduzione del distanziamento sulla seconda onda. Si vede come allentando (o annullando) il distanziamento la seconda onda indica livelli più elevati di contagio.

![Figura 3. Densità di infetti nel tempo per diversi indici (moderati) di distanziamento.](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.03.png>)

La figura 4 corrisponde a elevati livelli di distanziamento che conducono a una riduzione del livello del numero di infetti.

![Figura 4. Densità di infetti nel tempo per diversi indici (elevati) di distanziamento.](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.14.png>)

La figura 5 studia invece la dinamica della variante rispetto al virus primario. La variante, se presenta livelli più elevatidi capacità infettiva, tende a prevalere sul virus primario.

![Figura 5. Densità di infetti nel tempo: da virus primario (blu) e da variante (arancione).](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.20.png>)

{% hint style="info" %}
**Osservazione**. Il modello matematico è in grado di visualizzare non solo l’andamento nel tempo del numero di infetti, ma anche del livello di infezione e quindi sulla domanda di livello di ospedalizzazione, fino a individuare la necessità di terapia intensiva.
{% endhint %}

È  utile precisare meglio il significato di `distanziamento`: si intende l’insieme di azioni, generalmente indotte da normative, che riducono, o proteggono, il contatto fisico fra persone (mascherine, etc.). Questa entità fisica-sociale misura sia la probabilità di contatto e sia l’entità dell’infezione iniziale o `carico virale iniziale`. Nei modelli matematici il distanziamento è misurato da un parametro con valori da 0 a 1, che corrispondono, rispettivamente, a chiusura totale e apertura senza limiti. Il distanziamento determina inoltre la previsione di decessi.

A partire da queste simulazioni osserviamo i possibili effetti di un programma di vaccinazione nelle due figure che seguono.

La figura 6 corrisponde ad un caso specifico di variante a forte livello di capacità infettiva e quindi con forte prevalenza dellavariante sul virus primario.

![Figura 6. Densità di infetti nel tempo da virus primario (blu) e variante (arancione).](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.27.png>)

La figura 7 visualizza il ruolo di un processo di vaccinazione che corrisponde a una attivazione del sistema immunitario. Un forte piano di vaccinazione conduce alla riduzione del numero di infetti. Comunque non al completo annullamento diquesti.

![Figura 7. Densità di infetti nel tempo, da virus primario, variante e vaccinati (nero).](<../.gitbook/assets/Schermata 2022-01-23 alle 12.53.34.png>)

{% hint style="info" %}
**Osservazione.** Anche in questo caso, il modello matematico è in grado di visualizzare non solo l’andamento nel tempo del numero di infetti, ma anche del livello di infezione e quindi sul livello di ospedalizzazione, fino a individuare la necessità diterapia intensiva e i decessi.
{% endhint %}

### Interpretazione dei risultati

Queste simulazioni, ed il complesso di quelle che sono state prodotte dal team di lavoro [\[2, 4\]](riferimenti-bibliografici.md), conduce alle seguenti indicazioni:

* Anche dopo un elevato distanziamento, il virus continua a circolare e riprende vigore infettivo nell’onda successiva. Non appena il  distanziamento è allentato la seconda onda risulta tanto più dannosa quanto maggiore è la riduzione di quest’ultimo.
* La variante è di  norma più aggressiva del virus primario ed è predominante, soprattutto nella seconda onda. La riduzione del distanziamento contribuisce al predominio della variante.
* Un piano di vaccinazione continuo riduce di molto, soprattutto nella seconda onda, il numero degli infetti. Tuttavia, non annulla la  circolazione del virus. Questo riprenderà nel momento in cui il distanziamento sarà rilassato (o peggio annullato).
* Un piano di vaccinazione non elimina il predominio della variante. Il modello indica come sia possibile anche il contagio dei vaccinati. Questi tuttavia richiedono livelli inferiori di terapia. Inoltre, il modello indica come la circolazione del virus porta all’infezione dei  vaccinati quantitativamente più intensa quanto più circola  l’infezione del virus.

### Ulteriori sviluppi della ricerca

A conclusione di questa sezione, è utile chiedersi come la ricerca potrebbe (dovrebbe) ulteriormente svilupparsi. Proponiamo di indirizzare il focus su tre punti, fra i vari possibili. Di questi il terzo è quello maggiormente utile al dialogo con la società.

1. Approfondire lo studio della complessa interazione fra virus e risposta immunitaria, tenendo conto dell’eterogeneità soggettiva della risposte del sistema stesso.
2. Costruire un simulatore della dinamica del virus sui tessuti di organi, in particolare il polmone, tenendo conto di come il virus ne altera le proprietà. Studi in tal senso sono stati sviluppati in riferimento alla fibrosi polmonare [\[6\]](riferimenti-bibliografici.md), vedi figure 9 e 10 che visualizzano, in rosso, il progredire del deterioramento del tessuto polmonare a causa dell’azione del virus.
3. Utilizzare i modelli attualmente disponibili per sviluppare un simulatore della risposta del sistema tenendo conto delle esigenze del processo decisionale dei gestori dei problemi di crisi. Il simulatore potrà poi essere strutturato come strumento di intelligenza artificale a supporto del processo decisionale.

