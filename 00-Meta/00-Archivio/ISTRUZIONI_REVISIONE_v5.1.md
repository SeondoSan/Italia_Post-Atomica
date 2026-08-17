# ISTRUZIONI REVISIONE v5.1 — DEMOLIZIONE CONTROLLATA
**Data**: 14 Agosto 2026
**Origine**: Revisione d'autore di Secondo (agosto 2026) + canone Fase Creativa Chat 01-02
**Esecutore previsto**: Claude Sonnet (via Cowork o chat)

---

## ⚠️ COME USARE QUESTO DOCUMENTO — LEGGERE PRIMA DI TUTTO

**REGOLA FONDAMENTALE: UN FILE ALLA VOLTA.**

Per ogni sessione/task di lavoro:
1. Carica SOLO questo documento di istruzioni + IL SINGOLO file da modificare
2. NON caricare l'intero repository — la context window si satura e la qualità crolla
3. Applica: prima le REGOLE GLOBALI (Sezione A), poi le istruzioni specifiche del file (Sezione C)
4. Produci il file COMPLETO riscritto, non un diff
5. Il contenuto tagliato NON si cancella: si sposta nel file archivio corrispondente (vedi Sezione A.4)
6. In caso di dubbio: NON inventare, NON decidere. Inserisci `<!-- NOTA: [dubbio] -->` nel punto esatto e prosegui
7. Spunta la checklist finale (Sezione D) prima di consegnare

**Ordine di esecuzione consigliato**: Modulo 05 → 04 → 03 → 02 → 06 → 07 → 08 → 09 → 01 (indice per ultimo, così riflette lo stato finale).

---

## SEZIONE A — REGOLE GLOBALI (valgono per OGNI file)

### A.1 — Eliminazioni globali
I seguenti elementi vanno RIMOSSI ovunque compaiano (testo, link, tabelle). Il testo rimosso va in archivio (A.4):

| Elemento | Motivo |
|----------|--------|
| MnemoPulse / MemorItalia / Progetto Oblio | Proposta AI mai approvata |
| Sindrome dell'Eco | Derivata da MnemoPulse |
| Figli del Silenzio | Derivati dal controllo mentale eliminato |
| Figli della Verità, Centuria Mercuriale, Guardiani dei Semi, Recuperatores | Placeholder mai sviluppati |
| Lega dei Navigli (come organizzazione al 2293) | Non esiste al Punto Zero |
| Confederazione del Mare Dolce (al 2293) | Non esiste al Punto Zero — può nascere nell'Atto 2 |
| Fratellanza Alpina (come organizzazione strutturata) | Sostituita da: brigantaggio alpino, piccole bande (vedi A.3) |
| "Nuova Via della Seta" delle Famiglie | Incompatibile con Mediterraneo bloccato |
| Sincretismo religioso-tecnologico, Tecnosanti, Tecno-Reliquiari e ogni fusione mistica fede/tecnologia | Il controllo della Chiesa è pragmatico, non mistico. UNICA eccezione: le "benedizioni" delle celle di fusione (propaganda consapevole, non misticismo) |
| Etichetta "Rinascimento" in ogni sua forma (Nuovo Rinascimento, Rinascimento Militare, Sistema Rinascimento, estetica rinascimentale) | Cliché. L'estetica di riferimento è anni '50 atompunk in salsa italiana |
| Riferimenti espliciti al Medioevo storico reale come paragone | Il medievalismo è una scelta diegetica della Chiesa, non va spiegato con paragoni d'autore |

### A.2 — Sostituzioni globali di nomenclatura

| Da | A |
|----|---|
| Sette Isole Sacre | Arcipelago Centrale (nome descrittivo; eventuale nome proprio `[DA DEFINIRE IN FASE CREATIVA]`) |
| Gondolieri | Palustres |
| Grande Palude | Alto Mare Dolce |
| Papa Innocenzo X / Clemente XV / Romualdo Savellini | Papa Aeternus Primus (prebellico: Clemente XVI) |
| Tecno-Sacerdoti | Artifex |
| Muraglia Alpina | Corazza Alpina |
| "ghoul" riferito ai Palustres | I Palustres NON sono ghoul: sono mutanti anfibi distinti |

### A.3 — Canone di riferimento rapido
Se il file contraddice questa tabella, vince la tabella:

| Elemento | Valore canonico |
|----------|-----------------|
| Punto Zero | 2293 |
| Bombe | Ottobre 2077 |
| Innalzamento mare | +30 metri |
| Capitale prebellica | Napoli (dal 2042) |
| Bunker di Gaeta | Costruito PRIMA del 2077 come rifugio papale segreto. Clemente XVI è già lì quando cadono le bombe |
| Papa Aeternus | Ghoul dal ~2077-2090, unico a saperlo. Nessuna "fondazione 2207" |
| Parthenope Vaticana | Monte Orlando (Gaeta), prende forma 2120-2150 |
| Tabula Rasa | 2090-2100 (distruzione libri/prove, stile Fahrenheit 451: non demolizione di edifici, ma servizi segreti che bruciano terminali, libri, cartelloni. Chi conosce la verità = trattato come complottista) |
| Pirati Ghoul | 2077 nave da crociera a tema pirati al largo dell'Albania → 2077-2090 horror a bordo → 2090-2200 periodo balcanico → 2200-2250 navigazione a Ovest → 2250 arrivo e incidente con guardie pontificie → 2252-2255 Prima Crociata → guerra permanente. Al 2293: ~250-350 individui |
| Custodi | SIGILLATI nel vault sotto Castel Sant'Angelo al 2293. Escono DOPO il Punto Zero. Qualsiasi data di apertura (es. 2277) è ERRORE |
| Santi Mario ed Eugenio Custodi | CANONE: il vault richiede chiusura dall'esterno; i due restano fuori e si sacrificano per sigillarlo (2077). Canonizzati dalla Chiesa Custodiale. Iconografia: due statue ai lati delle porte. Fondatore della comunità: Don Eugenio Menini, che scopre la trappola di Clemente XVI |
| Chiesa Custodiale | Simbolo: colomba. Cristianesimo umanistico, monarchia elettiva. Interna al vault fino al 2293 |
| Palustres | Mutanti anfibi (NON ghoul), allevati in cattività nella laguna veneziana sommersa, sedati col brew, 4 stadi di progressione, Stadio 4 usato come contaminante biologico |
| Città distrutte | Milano, Venezia, Torino, Roma, Genova, Bologna = crateri/sommerse. MAI insediamenti attivi |
| Nord al 2293 | Comunità piccole, frammentate, tollerate. NIENTE organizzazioni formali |
| Armi da fuoco | Rarissime e clandestine. Popolazione: armi bianche, balestre, archi |
| Imbarcazioni a motore | <10 in tutta Italia, quasi tutte papali |
| MegalopolIT | Inizia nel Decennio Buio (2050-2060) come risposta alla scarsità ("siamo senza energia per colpa dei rossi, uniamoci"); rete canali completata ~2060-65 |

### A.4 — Procedura archivio
- Nella root del repo esiste (o va creata) la cartella `_ARCHIVIO/`
- Un file per modulo: `_ARCHIVIO/scarti-modulo-02.md`, `scarti-modulo-03.md`, ecc.
- Ogni blocco tagliato si APPENDE lì con intestazione:
  ```
  ## [nome-file-origine] — [titolo sezione] — rimosso v5.1
  Motivo: [una riga]
  [testo originale]
  ```
- Niente si perde: l'archivio è ripescabile da eventuali contributori futuri

### A.5 — Marcatori
- `[DA DEFINIRE IN FASE CREATIVA]` — elemento voluto ma non sviluppato
- `[PLACEHOLDER - MODIFICABILE DAI CONTRIBUTORI]` — contenuto flessibile, adattabile alle storie della community
- `<!-- NOTA: ... -->` — dubbio dell'esecutore, da rivedere con Secondo

---

## SEZIONE B — FILE DA ELIMINARE O CREARE

### Eliminare (contenuto → archivio, poi rimozione file e link)
- `05.3-lega-navigli.md`
- `07.3-lupi-roma.md` (cliché)

### Creare (vuoti con struttura, contenuto in fase creativa)
- `02.5-geografia-prebellica.md` — canali, città, porti, aziende, punti d'interesse (servirà a stabilire i bombardamenti)
- `06.2-arcipelago-centrale.md`
- `06.3-alto-mare-dolce.md`
- `08.5-comunicazioni.md`
- `08.6-energia.md`
- `00_TIMELINE_MASTER.md` — con le date della tabella A.3

---

## SEZIONE C — ISTRUZIONI FILE PER FILE

### MODULO 02 — STORIA

**02.0-situazione-prebellica-panoramica.md**
- Nomi delle industrie belliche: sostituire ogni nome reale con `[NOME AZIENDA - DA DEFINIRE IN FASE CREATIVA]`
- Rafforzare il tema: superamento della "sea blindness" italiana, il mare come centro di tutto, propaganda marittima
- Rete canali: mantenere ma marcare `<!-- NOTA: fattibilità e tracciato da studiare in fase creativa -->`
- Tecnologie di manipolazione della memoria: RIMUOVERE (→ archivio, motivo: non core, eventualmente per contributori)
- Tabula Rasa: mantenere il concetto secondo A.3 (Fahrenheit 451, non demolizione). Il nome resta con `<!-- NOTA: valutare nome più adatto -->`
- Timeline Pirati: allineare ad A.3
- Resto della timeline: invariato

**02.1-nuova-italia.md**
- SPOSTARE il progetto MegalopolIT: qui solo le premesse (potenza marittima). Il progetto vero parte nel Decennio Buio (vedi 02.2)
- Napoli: punto nevralgico sul mare → capitale dal 2042
- RIMUOVERE "Nuovo Rinascimento" e tutto il suo apparato → sostituire con boom in stile anni '50 americani adattato all'Italia: industria bellica in espansione, nuove fabbriche, controllo di stretti e ZEE come motore geopolitico
- Mode/vestiario: base look italiano anni '50, con nota `[DA DEFINIRE IN FASE CREATIVA: influenze propaganda marittima su estetica]`

**02.2-decennio-buio.md**
- Inserire qui l'avvio di MegalopolIT come risposta alla scarsità: "siamo senza energia per colpa dei rossi, dobbiamo unirci e fare sacrifici" — canali per trasporti quando la gomma non è praticabile. Completamento rete ~2060-65
- "Ora Luminosa" e "Cattedrali di Luce": mantenere i concetti, marcare i nomi `<!-- NOTA: nomi da rivedere -->`
- Esplicitare: la Chiesa riprende/consolida l'influenza sulla popolazione in questo periodo; il cattolicesimo resta religione di fatto ufficiale (in questo universo nessuno l'ha mai ridimensionata politicamente)

**02.3-italia-militare.md**
- RIMUOVERE l'etichetta "Rinascimento Militare" e TUTTA la sezione estetica collegata (design artistico, linee eleganti, eredità rinascimentale, personalizzazione) → archivio
- Costruire il colpevole narrativo: "i rossi ci hanno privato dell'energia per 10 anni — armiamoci" (radicato già nel 02.2)
- CENTRALE e da mantenere: l'Italia come fornitore di armamenti degli USA (che non producono abbastanza armi convenzionali, concentrati su robot e armature atomiche) + doppio gioco verso il fronte rosso. Marcare `<!-- NOTA: verificare plausibilità con canone Fallout, inclusa serie TV -->`
- "Protocollo Tripartito": ridimensionare — non un accordo formale, ma intese informali e infiltrazioni
- "Tecnologie Distintive Italiane": RIMUOVERE → archivio, sostituire con `[DA DEFINIRE IN FASE CREATIVA: eventuali esclusive tecnologiche italiane]`
- Nomi aziende: come 02.0
- Muraglia → Corazza Alpina (A.2)
- RIMUOVERE MnemoPulse/MemorItalia. MANTENERE Fortezza Futura e R.I.R. (il R.I.R. perde ogni collegamento a Oblio). Ri-Genesis: mantenere con `<!-- NOTA: valutare collegamento col personaggio del Papa -->`

**02.4-tensioni-finali.md**
- Contenuto invariato
- AGGIUNGERE sezione breve "Estetica e propaganda della fine": cartelloni, spot per l'acquisto di Vault, paranoia quotidiana. Marcare `[DA AMPLIARE IN FASE CREATIVA]`

---

### MODULO 03 — GEOGRAFIA

**03.0-geografia-panoramica.md**
- Rimuovere Lega dei Navigli e Fratellanza Alpina (A.1). Al loro posto, dove serve, il fenomeno del **brigantaggio alpino**: piccole bande rare, tipo partigiani/Robin Hood, radici della futura fazione post-Punto Zero
- Arcipelago Centrale: aggiungere (nella prospettiva "verità nascosta") che lo Stato Pontificio MANTIENE artificialmente la radioattività della zona — per tenere lontani gli esterni e impedire l'uscita dei Custodi
- "Sette Isole Sacre" → A.2
- Arcipelago Campano: RIMUOVERE (un arcipelago basta) → archivio
- "Alpi Irradiate": mantenere il territorio, marcare `<!-- NOTA: la popolazione probabilmente non le chiama più "Alpi" — nome popolare da definire -->`
- "Terra dei Laghi": MANTENERE e promuovere a nome popolare dell'area nord (nuovi laghi sparsi)
- Anomalie morfologiche: mantenere SOLO la Grande Frattura (che comprende/attraversa l'Arcipelago Centrale). Rimuovere Colonne di Calabria, Spirale Siciliana, Pilastri Alpini → archivio. Aggiungere: "Possibilità di inserire strutture morfologiche notevoli `[PLACEHOLDER - MODIFICABILE DAI CONTRIBUTORI]`"
- Corridoio Appenninico: precisare che si tratta delle vie DI SUPERFICIE — distinto dal tunnel segreto sotto gli Appennini (cantiere incompiuto della Chiesa)

**03.2-grande-guerra.md**
- Invariato. Aggiungere in testa: `[PLACEHOLDER - MODIFICABILE DAI CONTRIBUTORI]`

**03.3 / 03.4 / 03.5 (regioni nord/centro/sud)**
- Aggiungere in testa a ciascuno: `[PLACEHOLDER - MODIFICABILE DAI CONTRIBUTORI: geografia adattabile alle storie, salvo elementi consolidati in A.3]`
- Rimuovere ogni riferimento a fazioni eliminate (A.1) e applicare A.2/A.3 (es. 03.3: il Nord NON è "stabile e prospero con Rete dei Navigli" — è frammentato in piccole comunità)

---

### MODULO 04 — SOCIETÀ

**04.0-societa-panoramica.md**
- RIMUOVERE "Sincretismo Religioso-Tecnologico" (A.1)
- "Rinascita Medievale e Neofeudalesimo": mantenere l'idea di fondo, marcare `[DA DEFINIRE IN FASE CREATIVA: gerarchie, titoli, struttura sociale]`
- Città-stato: da "cosa normale" a rara eccezione tollerata/nascosta — correggere il tono; link a fazioni eliminate rimossi
- RIMUOVERE "Sindrome dell'Eco" (A.1)
- RIMUOVERE "Respiratori" e "Cristallini" → archivio
- Popolazioni Isolate: mantenere i gruppi umani, RIMUOVERE le mutazioni specifiche

**04.2-economia.md**
- La Medaglia: mantenere come valuta, RIMUOVERE l'impianto "impero romano" → marcare `[DA RIDEFINIRE IN FASE CREATIVA: identità marittima della valuta]`
- RIMUOVERE: Distribuzione Geografica, Autenticazione e Sicurezza, Utilizzo Regionale → archivio
- Valore: aggiungere proposta "water standard" (coerente con Fallout) come `<!-- NOTA: da confermare -->`
- "Baratto e Scambio Diretto" → ridurre a un paragrafo semplice: baratto
- RIMUOVERE Sistema del Credito della Lega (A.1)
- Risorse Economiche Strategiche: sfoltire; RIMUOVERE certificatori di purezza e assaggiatori d'acqua → archivio
- Rotte Commerciali e Mercati Specializzati: sfoltire pesantemente, rimuovere riferimenti a fazioni eliminate, l'eccesso → archivio con nota "sviluppabile dai contributori (rif. stile Kingsbridge)"
- AGGIUNGERE: la riscossione delle imposte ecclesiastiche non è regolare e "piacevole" — può avvenire in modo coatto all'occorrenza

**04.3-cultura.md**
- Sfoltire pesantemente: nel post-apocalisse domina l'ignoranza, non la cultura
- RIMUOVERE tecnosanti e ogni commistione fede/tecnologia (A.1)
- Ciò che si taglia → archivio; il file può ridursi a poche sezioni essenziali

**04.4-nuova-religiosita.md**
- RIMUOVERE ogni fusione fede/tecnologia (A.1), UNICA eccezione: benedizioni settimanali delle celle di fusione = propaganda consapevole della Chiesa

**04.5-memoria-collettiva.md**
- Correggere: i Custodi escono dal vault DOPO il Punto Zero (A.3)
- RIMUOVERE: controllo mentale, Figli del Silenzio (A.1)
- RIMUOVERE paragoni col Medioevo reale (A.1)
- Ridimensionare ogni "resistenza organizzata" al 2293: i semi della delegittimazione esistono ma sono invisibili
- AGGIUNGERE: `[DA DEFINIRE IN FASE CREATIVA: fazione nascosta sviluppata attorno a un super-computer/IA prebellico che conserva la conoscenza del passato, mai trovato dalla Chiesa — vault o altra struttura]`

---

### MODULO 05 — FAZIONI

**05.0-fazioni-panoramica.md**
- RIMUOVERE le voci Confederazione del Mare Dolce e Fratellanza Alpina con relative popolazioni (80-90k, 18k) → archivio
- Riconfigurare il panorama al 2293: Stato Pontificio dominante (~320.000 su ~430.000) + bande e piccoli gruppi frammentati che POSSONO crescere e diventare dissidenti `[DA SVILUPPARE IN FASE CREATIVA]`
- Pirati: secondo timeline A.3. Famiglie e Palustres: esistono, confermati

**05.1-stato-pontificio.md**
- CORREGGERE la fondazione: eliminare "2207, Papa Clemente XV (Romualdo Savellini)". La continuità è: Clemente XVI (prebellico, già a Gaeta nell'ottobre 2077) → diventa Papa Aeternus Primus. Non c'è successione
- Ridimensionare la "fondazione per intervento divino": la narrativa ufficiale parla di salvezza provvidenziale del Papa, senza eccessi

**05.2-citta-stato-nord.md**
- Riscrivere il frame: al 2293 non esistono città-stato come sistema. Possono esistere rare comunità ribelli/autonome nascoste `[DA SVILUPPARE IN FASE CREATIVA]`. Il contenuto attuale → archivio (utile per l'Atto 2)

**05.3-lega-navigli.md**
- ELIMINARE il file (Sezione B). Contenuto completo → archivio. Nota in archivio: la Lega può rinascere come fazione dell'Atto 2. La questione dell'origine delle maschere da peste (senza ancora Milano) resta `[DA DEFINIRE IN FASE CREATIVA]`

**05.4-fratellanza-alpina.md**
- Riscrivere: da organizzazione strutturata a fenomeno del **brigantaggio alpino** — bande piccole e rare, Robin Hood delle Alpi radioattive, embrione della futura fazione post-Punto Zero. Contenuto organizzativo attuale → archivio

**05.5-famiglie.md**
- NON fare micro-modifiche: marcare l'intero file `[PLACEHOLDER - DA RISCRIVERE IN FASE CREATIVA: fazioni doppiogiochiste, casate, territori]`. Applicare solo A.1/A.2 (rimozione riferimenti obsoleti)

**05.6-custodi-tempo.md**
- Riscrivere secondo canone A.3: origine nel vault sotto Castel Sant'Angelo (2077, tradimento di Clemente XVI, Don Eugenio Menini organizza la resistenza), sacrificio dei Santi Mario ed Eugenio (chiusura esterna, statue ai lati delle porte), Chiesa Custodiale (colomba, cristianesimo umanistico, monarchia elettiva), 200 anni di autosufficienza (50→150 persone), SIGILLATI al 2293
- RIMUOVERE ogni riferimento ad apertura 2277 / attività nel mondo / dispersione post-apertura (quello è materiale post-Punto Zero: → archivio con nota "Atto 1/2")
- Il ruolo futuro (nuovo papa condottiero, alleanza con Pirati e popolo) NON va nel file: `[DA DEFINIRE IN FASE CREATIVA: ruolo dei Custodi nell'Atto 1]`

---

### MODULO 06 — LUOGHI

**06.1-parthenope.md**
- CORREGGERE l'origine: il bunker di Gaeta è costruito PRIMA del 2077 come rifugio papale segreto — la fondazione NON è una reazione alla perdita di Roma. Timeline: A.3 (2120-2150 la capitale prende forma)
- Sfoltire: mantenere solo geografia essenziale (Monte Orlando, Castello Angioino-Aragonese, laguna-darsena, galleria sotterranea) e rimandare i dettagli: `[DA SVILUPPARE SE/QUANDO VI SI AMBIENTANO STORIE]`

**06.4-altri-centri.md**
- Sfoltire pesantemente: rimuovere i luoghi specifici inventati → archivio (i contributori ambienteranno le loro storie)
- MANTENERE e mettere al centro il principio: la popolazione uscita dai vault trova i castelli sparsi per l'Italia e vi si stabilisce per sicurezza → la vita si sviluppa attorno a castelli e fortificazioni (~750), ma non è una regola ferrea

**06.5-terre-selvagge.md**
- Idea di base giusta: sfoltire pesantemente, rimuovere l'obsoleto (A.1/A.2), eccesso → archivio

---

### MODULO 07 — CREATURE

**07.0 / 07.1 (panoramiche)**
- Applicare A.1/A.2. CORREGGERE ovunque: i Palustres NON sono ghoul (né "ghoul acquatici") — mutanti anfibi distinti
- Aggiornare gli elenchi creature dopo le eliminazioni sotto

**07.2-palustres.md**
- Allineare COMPLETAMENTE al profilo di FASE_CREATIVA_Chat01/02 (origine vault veneziano, allevamento in cattività nella laguna sommersa, brew, 4 stadi, Stadio 4 contaminante). Rimuovere "ghoul" dal titolo/descrizioni

**07.3-lupi-roma.md**
- ELIMINARE il file (cliché). Contenuto → archivio

**07.4-chimere.md** (Chimere Acquatiche)
- ELIMINARE il contenuto → archivio. Il file può restare vuoto con `[PLACEHOLDER]` o essere rimosso — `<!-- NOTA: decidere se tenere il file come contenitore futuro -->`

**07.5-altre-creature.md**
- MANTENERE: Marmotte — sostituire "telepatiche" con capacità a ultrasuoni stordenti (effetto flashbang)
- MANTENERE con nota: Ratti Corazzati e Cinghiali Corazzati `<!-- NOTA: valutare origine comune -->`
- ELIMINARE → archivio: Sussurratori, Sciami Intelligenti, Aquile di Ferro, Neo-Trogloditi, Figli del Fuoco, Tartalupi, Mantimurene, Colonie Radianti, Ombre Predatrici

---

### MODULO 08 — TECNOLOGIA

**08.0-tecnologia-panoramica.md**
- ELIMINARE → archivio: Tecno-Reliquiari, Recuperatores, Centuria Mercuriale, Gilde dei Calibri, Progetto Rinascimento Militare, Caratteristiche Distintive del Design Italiano, Sistema Rinascimento, Miti Tecnologici
- "Operazione Nuova Cartagine": mantenere l'operazione, marcare `<!-- NOTA: nome da cambiare, meno impero romano -->`
- "MicroFusione Mediterranea": ridimensionare — la tecnologia italiana NON supera quella americana
- ELIMINARE Sistema "Metamateriali Modulari" (M³) → archivio
- "Recupero Tecnologico Recente (2277-2293)": mantenere il concetto, marcare `[DA STABILIRE IN FASE CREATIVA]`

**08.1-tecnologie-prebellica.md**
- Applicare A.1/A.2/A.3 (in particolare: niente estetica rinascimentale, cap tecnologico sotto gli USA, nomi aziende → placeholder)

**08.2-armamenti-moderni.md**
- SVUOTARE l'elenco di armi con nomi propri → archivio integrale. Il file resta con: principi generali (livelli d'armamento 1-4 già canonici) + `[PLACEHOLDER - MODIFICABILE DAI CONTRIBUTORI]`

**08.3-traffico-armi.md**
- RISCRIVERE la premessa: siamo in Italia — le armi da fuoco NON circolano liberamente. La popolazione ha al massimo armi bianche (stiletti, balestre, archi). NIENTE mercati d'armi aperti
- Le armi che circolano sono clandestine: spacciate dalle Famiglie con la complicità di alcuni vescovi che arrotondano. I banditi ne hanno poche — costose, munizioni comprese. Scarsità = valore
- ELIMINARE i "Certificatori" → archivio
- Rimuovere ogni riferimento a elementi già eliminati (A.1)

**08.4-arsenali-perduti.md**
- Marcare in testa: `[PLACEHOLDER - PROPOSTE NON CONFERMATE: contenuti da validare in fase creativa]`. Il concetto (depositi perduti, anche di medaglie) è approvato; i singoli arsenali elencati NO. Applicare A.1 (rimuovere collegamenti a Oblio per il R.I.R.; Base Etna resta placeholder). Correzione già nota: l'Arsenale Vaticano è in zona occupata dai Pirati — la Chiesa non vi accede

---

### MODULO 09 — VAULT

**Tutti i file (09.0 → 09.6)**
- MANTENERE: informazioni generali come `[PLACEHOLDER]`, Bunker di Gaeta (secondo A.3), vault veneziano dei Palustres, vault dei Custodi (Castel Sant'Angelo, sistema matrioska, chiusura esterna)
- RIMUOVERE → archivio: numerazioni specifiche non ancorate (Vault 109, 250, V-01, RF-XX), esperimenti/sistemi di controllo mentale (09.4 si svuota quasi del tutto), sopravvissuti notevoli non canonici
- Posizionamento degli altri vault: `[DA DEFINIRE IN FASE CREATIVA]`

---

### INDICE — 01.0-indice-principale.md (ULTIMO)
- Aggiornare l'albero ai file effettivi post-revisione (eliminati, creati, rinominati)
- Correggere i link secondo la struttura reale
- Rimuovere la voce Modulo 10 mantenendo la nota di eliminazione

---

## SEZIONE D — CHECKLIST PER OGNI FILE COMPLETATO

- [ ] Regole globali A.1/A.2 applicate (cerca testualmente ogni voce delle tabelle)
- [ ] Nessuna contraddizione con la tabella canone A.3
- [ ] Contenuto tagliato APPESO al file archivio del modulo, con motivo
- [ ] Marcatori usati correttamente (A.5), dubbi segnalati con `<!-- NOTA -->`
- [ ] Link interni funzionanti (nessun link a file eliminati)
- [ ] File consegnato COMPLETO (non diff, non estratto)
- [ ] Niente inventato oltre le istruzioni

---

## SEZIONE E — NUOVI ELEMENTI PER LA PROSSIMA FASE CREATIVA
*(non toccare durante la revisione — solo promemoria)*

1. **Super-computer/IA prebellico**: fazione nascosta attorno a una IA che conserva la conoscenza del passato, mai trovata dalla Chiesa (vault o altro). Da sviluppare
2. **Ruolo Custodi nell'Atto 1**: nuovo papa condottiero che sconfigge Aeternus con Pirati, popolo e protagonista — concetto proposto, mai fissato: da consolidare
3. **Nome/dettagli San Mario**: rapporto con Eugenio, competenze, momento del sacrificio (aperti dal 2025)
4. **Origine maschere Lega dei Navigli**: da riscrivere senza Milano (per l'Atto 2)
5. **Rete canali prebellica**: studio di fattibilità narrativa (Climate Central + logica MegalopolIT)
6. **Estetica**: mix anni '50 italiani + propaganda marittima (sessione dedicata già pianificata)
7. **Nomi**: aziende belliche, "Tabula Rasa", "Ora Luminosa", "Cattedrali di Luce", "Nuova Cartagine", nome popolare delle Alpi

---

*Fine istruzioni v5.1 — eseguire un file alla volta, sempre.*
