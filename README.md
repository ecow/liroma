# LIROMA

MY-FI LIstening ROom Modelized by Auralization and other digital processing

![a wonderful listening room](images/liroma.png)


> **CALL FOR ACTION: please help me with english translation**

## Abstract

Questo progetto si propone di utilizzare le tecnologie di spazializzazione dei segnali audio, le tecnologie di convoluzione e auralizzazione per realizzare una sala d'ascolto immersiva a relativo  basso costo in cui replicare l'esperienza emotiva che si ottiene con diverse tipologie e configurazioni di impianti HI-FI. 

Il sistema vuole essere in grado di riprodurre l'immagine sonora (i.e. il "palcoscenico") e la timbrica desiderate partendo da una qualsiasi sorgente audio digitale, indipendentemente dalla sua codifica, formato, risoluzione e dal suo numero di canali.

## Razionale

Per un musicista, soprattutto nella musica POP, è ormai cosa normale registrare le proprie parti utilizzando una strumentazione virtuale, ottenuta attraverso la modellazione matematica di strumenti esistenti, più o meno antichi e/o iconici. I tecnici del suono, da molti anni, utilizzano compressori, equalizzatori ed effetti virtuali, cioè algoritmi digitali racchiusi in plugin in grado di simulare il comportamento di apparati fisici di difficile reperimento o molto costosi.
Ad esempio, il riverbero che ascoltiamo in moltissime registrazioni non è quasi mai reale: è solo una simulazione di quello che naturalmente si produce in spazi chiusi come cattedrali, teatri, studi di registrazione, jazz club. La impronta sonora dell’ambiente viene catturato in una funzione matematica, l'*impulso*, che poi viene composto (*convoluto*) al segnale di partenza per ottenere il risultato desiderato.

Il [prof. Angelo Farina](https://personale.unipr.it/it/ugovdocenti/person/18339) dell' Università di Parma si è spinto oltre, utilizzando la convoluzione e gli impulsi per predire e ascoltare l'acustica di teatri e sale da concerto *prima* di che vengano costruite.
Ciò è possibile attraverso un processo chiamato [auralizazione](https://en.m.wikipedia.org/wiki/Auralization) che convolve segnali audio registrati in ambienti anecoidi con un modello acustico del teatro sviluppato da opportuni software, e li trasforma in *audio immersivo* per un ascolto binaurale con normali cuffie come ben descritto in [questo articolo](http://pcfarina.eng.unipr.it/Public/Papers/119-Ciarm98.PDF).  È anche possibile sperimentare l'audio immersivo grazie ad una rete di altoparlanti indipendenti e coordinati a loro volta da sofisticati algoritmi di rendering audio basati sulle tecnologie [ambisonics](https://en.m.wikipedia.org/wiki/Ambisonics) o [SPS](http://www.angelofarina.it/sps-conversion.htm)

> *[Nota su audio immersivo]*
> 
> Molti già conoscono l'audio immersivo per averlo ascoltato al cinema o anche a casa propria grazie alle tracce multicanale Dolby Digital e DTS, oggi presenti anche in molti servizi di streaming. L'ascolto di tali tracce richiede una configurazione fissa di altoparlanti, che vanno  posizionati in una geometria ben definita per ottenere i risultati spaziali previsti dal regista.  Stanno prendendo sempre più piede formati di audio streaming basati su audio spaziale e pensati per un ascolto in cuffia
 
> *[Nota su riproduzione sonora HI-FI]*
> 
> Il mondo della riproduzione sonora domestica rimanda immediatamente al concetto di Alta Fedeltà (HI-FI) che ha avuto il suo boom a partire dagli anni 70 con la produzione di innumerevoli apparati audio/video, alcuni dei quali sono diventati oggetto dei desideri di generazioni di *audiofili* e collezionisti. A onor del vero, nel modo HI-FI il concetto di audio multicanale è spesso declinato nella sola stereofonia anche se esistono esperimenti notevoli in ambito quadrifonico, 3 canali e l’utilizzo HI-FI di di configurazioni di derivazione cinematografica (super audio cd, DVD audio, BluRay Audio, Dolby ATMOS)  per formati solo audio. 

La estrema soggettività sul giudizio estetico relativo ad una riproduzione sonora ha, più recentemente, fatto emergere la nozione di [MY-FI](https://www.afdigitale.it/my-fi-audio-una-necessaria-e-logica-personalizzazione/) che prende atto dell'impossibilità di avere un *impianto perfetto* ovvero ben suonante in qualsiasi ambiente e su qualsiasi genere musicale. Infatti anche l'ascolto del segnale "così come registrato" in uno studio di produzione, molto spesso non risulta soddisfacente da un punto di vista meramente edonistico; spesso infatti molti audiofili etichettano tale suono come affaticante, freddo, eccessivamente dettagliato, etc.,etc. 

Di fatto il mercato degli apparati per la riproduzione audio di qualità è suddiviso in due grandi segmenti: *PRO* e *HI-FI*. IMVHO, il primo si rivolge a chi cerca la massima fedeltà al segnale registrato  (che spesso è ben altra cosa rispetto alla fedeltà rispetto all'evento sonoro originale a causa di innumerevoli rilavorazioni in sede di editing e post-produzione), il secondo a chi predilige la piacevolezza di ascolto o una evocazione emotiva dell'evento originario (che molto spesso nessuno, per le ragioni di cui sopra, ha mai davvero potuto ascoltare).

Oggi esistono [standard](https://www.aes.org/e-lib/browse.cfm?elib=4782) per una sala di ascolto "pro", ovvero le control-room,  in virtù dell'esistenza di un riferimento ultimo oggettivo mirato alla riduzione di qualsivoglia colorazione del segnale originale (ovvero il "master" ), ma non esistono standard per un ascolto di tipo *HI-FI* in cui alcune colorazioni sono addirittura volute: si pensi al suono prodotto dalla naturale saturazione delle valvole. Occorre anche dire che, anche  in assenza di standard, alcune esperienze di ascolto HI-FI sono riconosciute appaganti, se non universalmente almeno a grande maggioranza; ad esempio sono pochi quelli che non si emozionano ascoltando la voce di Louis Armstrong su una coppia di vecchie casse elettrostatiche. Peccato però che lo stesso impianto, alle prese con una moderna registrazione di musica elettronica risulti del tutto inadeguato a riprodurre la necessaria pressione sonora. Situazione inversa se si prendono in considerazione impianti di alta qualità basati su diffusori a tromba ad alta efficienza.

In sostanza si può affermare che ogni impianto possiede una propria fisionomia risultante dalla combinazione di apparati, tipologogia della musica preferita, segnale sorgente e ambiente di ascolto inteso nella sua accezione più ampia che comprende la geometria della stanza, i materiali con cui è costruita, l'arredamento, il trattamento acustico, la collocazione degli apparati audio fino ai più minuti accessori dominio degli appassionati di *fine tuning*. 

## Obiettivo del progetto

Questo progetto si propone di utilizzare le moderne tecnologie di rendering audio, le tecnologie di convoluzione e auralizzazione per realizzare una sala d'ascolto domestica in cui replicare l'esperienza emotiva che si ottiene con diverse tipologie di impianti HI-FI. Il tutto a costi limitati e permettendo di cambiare virtualmente impianto anche ad ogni brano musicale, adattandolo al proprio gusto estetico.

L’idea alla base del progetto è di descrivere tramite strumenti matematici (i.e. impulsi):
1. la funzione di trasferimento di sala di ascolto di riferimento in cui opera una configurazione di componenti per la riproduzione audio (*ambiente target*)
2. la funzione di trasferimento della propria sala di ascolto

Utilizzare poi queste funzioni per computare una trasformazione del segnale in ingresso che replichi, nel proprio ambiente domestico, l'esperienza di ascolto nell'ambiente target.

L'insieme dei vincoli cui il progetto è assoggettato lo collocano nel dominio del puro entertaiment anche se, con le opportune tare, potrebbe essere considerato un POC per un progetto più ambizioso.

Se l’obiettivo teorico fosse infatti pienamente raggiunto, semplicemente cambiando solo la prima delle funzione in ingresso, sarebbe possibile ascoltare un segnale registrato così come riprodotto da un qualsiasi impianto (pro o hi-end) senza alcuna modifica fisica al proprio sistema di riproduzione. Ad esempio ascoltare Luis Amstrong con casse elettrostatiche, o un solo di Marcus Miller con un potente sistema a trombe ma anche mixare l'audio di un filmato in formato stereo, 5.1, 7.1 e Dolby ATMOS.


## How it works

well... how it *COULD* work is simplified in this wokflow:


![how it woks](images/how-it-works.png)

the main open point is how to capture the footprint of the target HI-FI system. In a first step a *trial and error* approach can be used.

Some well known re-mastering tecniques (linear phase equalization, multiband compressions, reverberation, etc. etc.) can be also applied in real time to the source signal according your personal taste.

## Vincoli
Nonostante il tentativo di operare in modo più possibile scientifico, è ragionevole ipotizzare che nella pratica alcune condizioni ideali assunte dalla teoria non possano essere rispettate e quindi occorra scendere a compromessi. Tali compromessi renderanno i risultati di questo progetto comunque soggettivi e difficilmente replicabili. Con questa consapevolezza accettiamo di applicare i seguenti vincoli:

- la stanza dovrà essere principalmente dedicata all'ascolto, nel senso che il suo arredamento non deve mutare sovente nel tempo, per evitare di dover ricomputare ad ogni cambiamento la sua funzione di trasferimento.
- il sistema sarà ottimizzato per un unico punto di ascolto (*hot spot*), in modo non dissimile a quanto avviene oggi con un normale impianto stereo.
- la sala di ascolto dovrà essere trattata acusticamente per limitare le onde stazionarie e le prime riflessioni, almeno nell’hot spot
- la stanza di ascolto dovrebbe contenere da 12 a 16 casse acustiche indipendenti e almeno un sub woofer dedicato ai bassi sotto i 100Hz. L’utilizzo di uno o più sub è finalizzato a sia ridurre le dimensioni delle casse e quindi il loro costo ma anche a minimizzare i problemi con le fasi rendendo quanto più possibile le sorgenti puntiformi
- il segnale in ingresso sarà esclusivamente digitale, il che significa che eventuali sorgenti analogiche dovranno subire un processo di digitalizzazione *prima* di essere riprodotte
- il sistema di altoparlanti deve essere in grado di erogare nell’hot spot una pressione di **83 dB SPL** calcolato su con un segnale di calibrazione e permettere di avere un picco di SPL di almeno 103dB come consigliato da Bob Kats nel cap.14 del suo libro "Mastering Audio". Tale valore potrebbe essere incrementato a 93 dB SPL se si desidera seguire le specifiche [THX](http://www.acousticfrontiers.com/2013314thx-reference-level/) 
- il sistema di altoparlanti deve avere  una risposta di frequenza senza eccessive discontinuità almeno nel range 100-18K anche la rotazione di fase non dovrebbe avere eccessivi salti. Non è richiesta assoluta linearità
- il sistema di altoparlanti deve comprendere almeno un sub woofer in grado di emettere le frequenze da 20Hz con una pressione sonora di picco di 115db nell’hot spot in accordo con le specifiche THX. Si noti come tale requisito si rifletta sulla necessità nei fatti di avere uno o più subwoofer molto grossi e performanti
- la distorsione armonica indotta dall'amplificazione dovrebbe mantenersi sotto la soglia di 0.1 db
- la distorsione armonica delle casse sia più bassa possibile al valore di pressione nominale richiesto (che valore mettere come riferimento? come misurarlo?)
- il rumore di fondo totale deve essere molto basso, cioè circa nel range tra 20 e 30 dB SPL calcolato ad impianto acceso e segnale assente.

> Il progetto prevede un range dinamico utile di circa 80dB, pari a poco più di 13 bit e quindi parecchio inferiore al limite teorico di 96dB risultanti dalle specifiche di un CD, ma comunque molto superiore alla reale risoluzione nella quasi totalità delle registrazioni commerciali (vedi [loudness war db](https://dr.loudness-war.info/)). Ad aggiungere rumore si fa sempre in tempo, e [può essere conveniente farlo](https://www.musicradar.com/tuition/tech/10-ways-to-use-noise-to-enhance-your-mixes-633348) perché anche il rumore di fondo concorre alla fisionomia di un impianto e comunque la dinamica percepita non sempre coincide con quella teorica (come nel caso degli LP ad esempio). D'altronde il dithering è prassi consolidata, se non obbligatoria, anche nei processi di mastering.

> [Nota sulla linearità ]
> 
> Si osservi anche che la perfetta linearità di risposta in fase e in frequenza non è un requisito, ciò perché gli algoritmi di DRC (Digita Room Correction) e auralizzazione permettono di correggere sia fase che risposta in frequenza se entro ragionevoli limiti; inoltre la rotazione di fase e la non linearità di risposta in frequenza sono inevitabilmente introdotte da qualsiasi ambiente di ascolto che non sia anecoico e sono peraltro le principali componenti che caratterizzano una riproduzione audio. Va da se che anche l'assoluta linearità di risposta del sistema, obiettivo di un ascolto *Pro*, potrà essere solo approssimata, come del resto avviene nella quasi totalità dei project studio di piccole e medie dimensioni.

I seguenti vincoli sono poi utili per semplificare la complessità ddel sistema:

- le casse dovrebbero essere identiche o almeno molto simili, anche se gli algoritmi di DRC permettono  di armonizzare il suono di casse lievemente diverse
- le casse devono essere direzionali e proiettare il suono prevalentemente frontalmente (no dipoli) per poter predire e limitare le prime riflessioni
- il posizionamento delle casse dovrebbe essere preferibilmente simmetrico rispetto all’hot-spot; in una situazione ottimale le casse dovrebbero essere collocate simmetricamente sulla superficie di una sfera con al centro l'hot spot. Anche in questo caso è comunque prevista nel progetto una correzione dell’allineamento temporale e di e volume di emissione per compensare eventuali piccole differenze.
- la frequenza di campionamento per il trattamento dei segnali digitali è fissata a 48Khz con una risoluzione di 24bit al fine di limitare la potenza computazionale necessaria e per permettere di utilizzare linee di trasmissione economiche (8 canali su una singola fibra ottica ADAT). Si osserva come comunque tale frequenza e risoluzione siano ampiamente sufficienti a realizzare i vincoli di pressione acustica e SNR richiesti. Di contro, eventuali risoluzioni più alte o più basse sul segnale in ingresso richiederanno un preventivo ricampionamento non critico grazie agli algoritmi di down-sampling oggi disponibili.

## Requisiti funzionali

I requisiti funzionali del sistema sono raccolti in 5 macro aree:

- requisiti relativi ai **segnali in ingresso**, che evidenziano quali input sono compatibili con il sistema di riproduzione
- i requisiti relativi al **player**, ovvero lo strumento che si occupa di decodificare i segnali di ingresso standarizzandoli e applicando eventuali trasformazioni *a grana grossa*. Tale strumento si occupa anche di visualizzare eventuali video facendosi carico di compensare eventuali ritardi introdotti dalla la catena dei processori audio. La visualizzaione ottimale del video non è prioritaria in questo progetto.
- i requisiti relativi al **Digital signal processor**, ovvero lo strumento di effettuare le trasformazioni qualitative nei segnali di ingresso (remastering) e di rendering del suono in 3D. Rappresenta il cuore del sistema ed è realizzato attraverso una *pipeline* di processori audio digitali
- i requisiti funzionali relativi alla configurazione della **sala di ascolto**
- i requisiti relativi alle **applicazioni di controllo** tramite cui l’ascoltatore può interagire con il sistema (scelta brani, set-up volume, cambio configurazione di ascolto) tipicamente attraverso un tablet o un normale smartphone 

I principali requisiti funzionali sono raccolti nel seguente diagramma:

![functional view](images/functional-view.png)


## Deploy example

La seguente figura mostra una possibile configurazione logica per il deploy del progetto:

![deploy view](images/deploy-view.png)

Sono previste due aree fisiche distinte:
- un'area in cui collocare la strumentazione rumorosa, principalmente a causa di ventole e sistemi di raffreddamento dei processori
- una sala di ascolto con una geometria simmetrica rispetto all'hot spot.

## Vst host

Il cuore del sistema è senza dubbio la catena di processori digitali. L’ipotesi attuale in questo progetto (a sono graditi consigli e alternative) è di usare un VST host e una serie di plugin VST, a parità di qualità sono da preferire plugin con codice open source.

La pipeline di plugin prevista è sintetizzata nella seguente figura:

![vst host](images/vst-host.png)

## Come contribuire al progetto

Molti punti in questo progetto sono ancora aperti, per ciascuno di questi è disponibile un’area di [Polis](https://pol.is/home), usata come piattaforma conversazionale, nella speranza che emerga una opinione condivisa:

- [what’s the best digital prcessing pipeline manager: simple VST host or DAW?](https://pol.is/9wpnehy6ue)
- [SPS or ambisonics: what plugins?](https://pol.is/5ka3essadr)
- [Best buy suggestions for speakers and amp in LIROMA?](https://pol.is/8eardcdusj)

Ovviamente vi prego di segnalare ogni errore, omissione, richiesta di estensione nelle [issues](https://github.com/ecow/liroma/issues) di questo progetto.

Se avete realizzato qualcosa di simile e volete condividere la vostra esperienza segnalatemelo e provvedeò ad inserirlo in una sezione di questo progetto.


## Licenza

Il seguente progetto è Copyright by Enrico Fagnoni ed è rilasciato con licenza [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) il sw sviluppato specificamente per questo progetto è rilasciato con licenza [MIT](LICENSE) 


## References

Questo progetto nasce grazie ad alcuni straordinari lavori, ai cui autori va la mia più grande ammirazione:

- Angelo Farina [ambisonic pages](http://pcfarina.eng.unipr.it/ambisonics.htm)
- Alberto Amendola and Angelo Farina - [SPS](http://www.upv.es/contenidos/ISVA2011/info/U0568405.pdf)
- Michael Vorländer - [Auralization: Fundamentals of Acoustics, Modelling, Simulation, Algorithms and Acoustic Virtual Reality](https://www.amazon.it/Auralization-Fundamentals-Acoustics-Simulation-Algorithms/dp/3642080235)
- Bob Kats - [Mastering Audio: The Art and the Science](https://www.amazon.it/Mastering-Audio-Science-Bob-Katz/dp/0240818962).
- David Monacchi - [FRAGMENTS OF EXTINCTION](https://www.fragmentsofextinction.org/)
- Alaa Algargoosh and John Granzow [How can a room shape your voice?](https://acoustics.org/2aaa-developing-a-new-method-for-analyzing-room-acoustics-based-on-auralization-how-can-a-room-shape-your-voice/)