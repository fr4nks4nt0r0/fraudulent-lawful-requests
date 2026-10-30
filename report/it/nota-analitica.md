# La PEC certifica la casella, non l'autorità

*Nota analitica sul caso Revolut - Francesco Santoro - aggiornata al 28 ottobre 2026*

I codici tra parentesi (C001, C002…) rimandano alla matrice delle fonti in [`sources/claims.csv`](../../sources/claims.csv), dove ogni affermazione è valutata con il sistema Admiralty.

## Sintesi

In Italia una PEC certifica da quale casella parte una richiesta, ma non che chi scrive abbia il potere di farla.

Quest'anno Revolut ha consegnato dati di 680 clienti in risposta a richieste arrivate da una casella PEC autentica della Prefettura di Reggio Calabria, come ha confermato il ministro dell'Interno alla Camera (C001, C055, C056). Secondo la stampa, le richieste erano a nome della Polizia Postale (C033).

Le richieste superavano ogni controllo sul mittente, visto che la casella era effettivamente autentica. Tuttavia c'erano almeno cinque irregolarità verificabili:

1. un ufficio del Ministero dell'Interno che scrive a nome della Polizia di Stato;
2. una richiesta da Reggio Calabria per un'indagine della Procura di Milano (C030);
3. una Prefettura che chiede dati bancari;
4. il richiamo all'Ordine europeo di indagine, affare delle autorità giudiziarie e non di una Prefettura (C032);
5. numeri di protocollo di un'altra Procura, quella di Roma (C031).

Consultando i dati del registro IndicePA queste incoerenze emergono in poco tempo.

L'unica difesa che un attaccante preparato non supererebbe è la verifica diretta con l'autorità citata, che ad oggi non ha un canale istituzionale. Il problema diventa più urgente con il Regolamento UE e-Evidence, applicabile dal 18 agosto 2026, che rende normali le richieste dirette e transfrontaliere ai fornitori di servizi digitali, con risposte entro 10 giorni o 8 ore (C048, C054).

## IL CASO

### Le richieste

Il 12 settembre 2026 Revolut ha confermato di aver mandato file con i dati di clienti a un terzo che aveva inviato richieste di informazioni da un indirizzo di un dominio governativo legittimo (C001, C002). La banca non ha nominato né l'ente né il numero di clienti colpiti, parlando solo di un "numero limitato" (C028).

Il 30 settembre, rispondendo a un'interrogazione alla Camera, il ministro dell'Interno ha confermato che la richiesta è arrivata dalla casella PEC denominata "entilocali", riconducibile alla Prefettura di Reggio Calabria e "poi risultata mai utilizzata" (C055).

Le richieste sarebbero state presentate a nome della Polizia Postale (C033). Secondo Il Post, che ha esaminato gli screenshot della corrispondenza, citavano un'indagine della Procura di Milano, contenevano numeri di protocollo riconducibili alla Procura di Roma e richiamavano la direttiva UE sull'Ordine europeo di indagine (C030, C031, C032).

Gli screenshot sono stati diffusi da un account X che afferma di fare da tramite con gli autori (C041). Sono coerenti con le dichiarazioni di Revolut, ma la loro autenticità non è verificata (C017). Secondo l'analisi di KELA, mostrano uno scambio tra PEC: le richieste arrivavano alla casella PEC italiana di Revolut, gestita tramite InfoCert (C004).

### Durata e scoperta

Secondo la ricostruzione di Silere non possum, la casella è stata usata per le richieste almeno dal 24 marzo al 24 luglio 2026 (C034). Altre testate parlano di circa sei mesi: la durata è incerta (C035).

Revolut avrebbe scoperto l'inganno contattando l'ente per altre vie non specificate (C036). Negli screenshot pubblicati dall'attore, la banca chiede la distruzione dei documenti già inviati, sostenendo che i conti rientrano in un'altra giurisdizione (C037).

Il 12 settembre Revolut ha notificato un possibile incidente all'Agenzia per la cybersicurezza nazionale; il 15 settembre ha confermato di aver fornito dati di 680 clienti (C056), di 33 Paesi prevalentemente europei secondo Fanpage (C027). Revolut dichiara che i suoi sistemi e i fondi dei clienti non sono stati violati (C020).

### L'estorsione

Il 14 settembre il gruppo IAmNotAVillain ha aperto un sito di estorsione (C012). Il gruppo sostiene di possedere documenti KYC, selfie di verifica, recapiti, identificativi bancari e transazioni dei clienti (C003): una rivendicazione coerente con le categorie di dati indicate da Revolut nella notifica ai clienti (C001).

Il gruppo ha chiesto un riscatto di circa 3 milioni di dollari in monero (C029). Una richiesta di 10.000 bitcoin, attribuita da alcune testate allo stesso gruppo, secondo OCCRP era associata a un altro account, "Revolut Smilik" (C044, C063). Secondo Prima Pagina News, dopo il mancato pagamento gli autori avrebbero iniziato a vendere i dati e a contattare direttamente le vittime (C046).

### Il fronte italiano

Dal 25 settembre sul sito dell'attore compare una sezione "Italy" con documenti attribuiti ai ministeri dell'Interno e della Giustizia (C013). Secondo Cybersecurity360 includono dati di agenti di polizia, autorizzazioni per l'ingresso di armi e documenti d'identità (C019), oltre a una nota dell'ambasciata turca sull'annullamento di passaporti diplomatici (C014). L'autenticità dei documenti non è verificata (C018).

L'attore sostiene di possedere circa 147 GB di dati delle forze dell'ordine italiane (C015) e di aver monitorato la PEC della Prefettura per sei mesi (C016). Afferma inoltre che le vittime italiane sono salite da 8 ad almeno 15 (C045). Nessuna di queste affermazioni ha riscontri: interrogato in aula proprio sui 147 GB, il ministro non li ha né confermati né smentiti (C061).

### Le indagini

Secondo il ministro, il Centro operativo per la sicurezza cibernetica della Polizia di Stato ha informato la Procura di Reggio Calabria e sta indagando; l'ACN ha informato la Polizia Postale e la Direzione nazionale antimafia e antiterrorismo (C058). Secondo fonti di stampa, l'ipotesi è di accesso abusivo a un sistema informatico di interesse pubblico (C022). Revolut, soggetto di diritto britannico, non è sottoposta alla normativa nazionale NIS (C060). Il Ministero sta valutando misure nell'ambito del contratto Consip per le caselle PEC, senza escludere sanzioni al fornitore (C059).

Il 18 settembre il Garante privacy ha chiesto a banche e istituti finanziari di verificare eventuali comunicazioni anomale provenienti dalla stessa casella e ha avviato la cooperazione con l'autorità lituana, competente per Revolut (C062). Nel Regno Unito l'Information Commissioner's Office avrebbe aperto un'indagine dopo una segnalazione di Revolut (C039).

Il caso è arrivato in Parlamento con un'interrogazione alla Camera (PD), un'interpellanza urgente (Azione) e un'interrogazione al Senato (PD) (C064).

## Perché ha funzionato

L'attacco ha sfruttato la distanza tra ciò che una PEC certifica e ciò che le viene attribuito.

Una PEC certifica che il messaggio è partito da quella casella, quando è stato inviato e consegnato, e che non è stato alterato. Ma non garantisce chi ha materialmente scritto il messaggio, né, come in questo caso, che il titolare della casella abbia il potere di chiedere ciò che chiede. Se le credenziali vengono rubate, tutte le garanzie restano valide.

Secondo KELA lo scambio è avvenuto tra la PEC dell'ente e la PEC italiana di Revolut (C004): su quel piano non c'era nulla da rilevare. È significativo che la stessa analisi di KELA descriva il superamento dei controlli SPF, DKIM e DMARC (C042), cioè i controlli di autenticazione dell'email ordinaria. Il punto non era l'autenticazione tecnica del mittente, già garantita dalla PEC, ma la sua autorità.

Lo riconoscono anche le istituzioni: il Garante ha scritto che il caso ha evidenziato alcune debolezze del sistema PEC in uso (C062), e il ministro dell'Interno ha sostenuto che Revolut avrebbe dovuto accorgersi dell'incoerenza tra i dati richiesti e la fonte della richiesta (C057). Quest'ultima è la valutazione di una parte in causa, ma indica lo stesso punto debole.

Un dettaglio rafforza l'analisi: secondo il ministro la casella non era mai stata utilizzata (C055). La mia ipotesi, non verificata, è che una casella istituzionale attiva ma inutilizzata sia anche una casella che nessuno sorveglia.

## Cosa avrebbe potuto fermarlo

Cinque anomalie erano rilevabili prima di rispondere. Due (ente e territorio) erano verificabili con i dati di IndicePA, il registro ufficiale delle pubbliche amministrazioni; due (competenza e base giuridica) confrontando IndicePA con la norma; l'ultima (protocollo) richiede un controllo dell'operatore.

**Cosa mostra IndicePA** (mie verifiche sugli open data, settembre-ottobre 2026). La PEC di protocollo della Prefettura di Reggio Calabria è registrata sotto il Ministero dell'Interno (codice ente `m_it`), con dominio `pec.interno.it`. La Polizia di Stato è invece un ente distinto (codice `XZR4RNHR`), con un proprio dominio, `pecps.poliziadistato.it`, usato solo da quell'ente. La Procura di Milano è presente con indirizzo e telefono. Nel dataset dei domicili digitali delle unità organizzative non risulta invece alcuna casella "entilocali" della Prefettura (C065).

| Controllo | Esito nel caso Revolut |
| --- | --- |
| La casella esiste nel registro ufficiale? | **Da verificare**: la casella "entilocali" non risulta nel dataset consultato (C065). Se confermato, anche questo controllo sarebbe fallito |
| L'ente titolare della casella coincide con quello dichiarato? | **Fallito**: casella del Ministero dell'Interno, richiesta a nome della Polizia Postale |
| Mittente e autorità citata sono coerenti per territorio? | **Fallito**: ufficio a Reggio Calabria, indagine della Procura di Milano |
| L'ufficio ha la competenza per chiedere quei dati? | **Fallito**: una Prefettura che chiede documenti KYC e dati bancari |
| La base giuridica è coerente con il mittente? | **Fallito**: Ordine europeo di indagine citato da un ufficio che non è né autorità giudiziaria né polizia giudiziaria |
| Il protocollo è riconducibile al mittente? | **Fallito**: protocolli riconducibili alla Procura di Roma |

Il punto su cui concentrarsi è la prima riga. Anche nell'ipotesi più favorevole all'attaccante, cioè con una casella censita nel registro, il controllo sul mittente viene superato: una procedura che si ferma lì non ferma questo attacco.

La verifica che ha effettivamente scoperto la frode è stata un contatto con l'ente per altre vie (C036), arrivato dopo circa quattro mesi di richieste (C034).

## Limiti

I controlli di coerenza avrebbero fermato questo attaccante perché ha commesso errori piuttosto evidenti, che un attore più preparato non farebbe.

**Un attaccante preparato supera i controlli automatici.** Se compromette la casella dell'ente effettivamente "atteso", nella provincia della Procura citata, con una base giuridica nazionale plausibile e una scadenza normale, nessun controllo di coerenza lo rileva. I controlli alzano il costo dell'attacco, non lo rendono impossibile.

**La verifica fuori banda non ha un canale.** L'unico muro che non si supera semplicemente compromettendo una casella è la conferma diretta con l'autorità citata. Oggi però chi riceve una richiesta non ha un interlocutore designato presso le Procure, e la verifica dipende dalla disponibilità di chi risponde al centralino.

**La fiducia va legata al procedimento, non alla casella.** Un sistema che considera "affidabile" un mittente dopo il primo contatto abbassa la guardia proprio sull'attaccante. La fiducia va legata al singolo procedimento, verificato con l'autorità che lo conduce.

**IndicePA non basta.** Il registro copre solo le amministrazioni italiane e la qualità dei record varia.

**e-Evidence aggrava il problema.** Dal 18 agosto 2026 le autorità di un altro Stato membro possono chiedere dati direttamente ai fornitori di servizi digitali, come operatori telefonici, piattaforme e servizi cloud; le banche sono escluse (C048, C054). Il regolamento prevede un sistema informatico sicuro per trasmettere gli ordini, obbligatorio sulla carta (C050), ma non ancora operativo (C051). Nel frattempo valgono mezzi alternativi, che secondo la norma devono permettere al ricevente di stabilire l'autenticità della richiesta, senza però indicare come (C053). Per le autorità estere, inoltre, non esiste un registro equivalente a IndicePA consultabile da chi riceve gli ordini.

**Limiti di questa analisi.** La nota si basa solo su fonti aperte, e diversi fatti dipendono da screenshot non verificati (C017). Le indagini sono in corso e potrebbero modificare la ricostruzione.

## Raccomandazioni

| # | Per | Raccomandazione | Perché |
| --- | --- | --- | --- |
| 1 | Banche, fintech e provider che ricevono richieste | Controlli di coerenza obbligatori su ente, territorio, competenza e base giuridica, e callback all'autorità citata con numeri presi da fonti indipendenti | Nel caso Revolut avrebbero rilevato cinque anomalie |
| 2 | Ministero della Giustizia | Un punto di contatto presso ogni Procura, o un servizio centrale, per verificare l'autenticità delle richieste di dati | Rende praticabile la verifica fuori banda, oggi affidata alla buona volontà |
| 3 | Autorità giudiziaria e forze di polizia | Allegare sempre il provvedimento dell'autorità giudiziaria, firmato digitalmente e verificabile | Falsificare un provvedimento firmato è molto più difficile che usare una casella compromessa |
| 4 | Pubbliche amministrazioni | Autenticazione a più fattori, monitoraggio degli accessi anomali e disattivazione delle caselle PEC inutilizzate | Il furto di credenziali da solo non basterebbe più; la casella usata nell'attacco risultava mai utilizzata (C055) |
| 5 | Governo e Ministero della Giustizia, nell'attuazione di e-Evidence | Definire come chi riceve un ordine con mezzi alternativi possa verificarne l'autenticità, come chiede l'art. 19 del regolamento; nel frattempo, linee guida per i fornitori di servizi digitali | Il sistema sicuro non è operativo e la norma non dice come verificare gli ordini arrivati per altre vie, con scadenze fino a 8 ore (C051, C053) |
