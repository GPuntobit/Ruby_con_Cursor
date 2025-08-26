# Ruby con Cursor

Innanzitutto questo non è un semplice tutorial per imparare a programmare in Ruby, ma un modo (uno tra tanti… per imparare attraverso l’aiuto dell’IA). Ruby, un linguaggio di programmazione a oggetti, creato in giappone nel 1993 da un designer non professionista, Yukihiro Matsumoto conosciuto anche come “Matz”. Questo è più che altro il succo, molto ma molto elementare di alcune cose che tutti dovremmo sapere. 

Iniziamo con il piccolo corso, su come usare Cursor:

(da copiare e incollare, in un file nominato scaletta.md). Il “.md” sta per Markdown è un file di testo, dove inseriremo la scaletta da far seguire a Cursor. Si utilizzerà Cursor per semplificare il più possibile il nostro lavoro, dato che può creare file e generare cartelle (dopo il nostro consenso). Il nome prima di .md può variare o essere come più preferite.

#### Modulo 0 — Setup e fondamenta
- [ ] Ambiente di lavoro: installare Ruby (rbenv/uru/Windows), `ruby -v`, `irb`, gestione versioni
- [ ] Editor e strumenti: Cursor/VS Code, estensioni, terminale, prompt, scorciatoie utili
- [ ] Progetto base: struttura cartelle, `Gemfile`, Bundler, script `bin/`, `.gitignore`

#### Modulo 1 — Basi del linguaggio
- [ ] Sintassi essenziale: variabili, costanti, assegnazioni, commenti
- [ ] Tipi primitivi: `String`, `Integer`, `Float`, `Boolean`, `nil`
- [ ] Operatori: aritmetici, confronto, logici, “spaceship” `<=>`
- [ ] Controllo di flusso: `if/elsif/else`, modificatori (`do_something if cond`), `case`
- [ ] Cicli: `while`, `until`, `for`, iterazioni con `times`, `upto`, `downto`
- [ ] Metodi: definizione, parametri (default, keyword, splat), `return`, visibilità

#### Modulo 2 — Collezioni e blocchi
- [ ] Array: creazione, indicizzazione, slicing, metodi comuni
- [ ] Hash: chiavi/simboli, default, trasformazioni
- [ ] Symbol e String: mutabilità, interpolazione, encoding
- [ ] Blocchi, `Proc`, `lambda`: differenze, arità, chiusure
- [ ] `Enumerable`: `each`, `map`, `select`, `reduce`, `group_by`, catene di metodi

#### Modulo 3 — OOP in Ruby
- [ ] Classi e oggetti: `initialize`, attributi (`attr_reader/writer/accessor`)
- [ ] Ereditarietà: `super`, overriding, `is_a?` vs `respond_to?`
- [ ] Moduli: mixin, `include` vs `extend`, namespaces
- [ ] Metodi di classe vs istanza, `self`, singleton methods
- [ ] Incapsulamento: `public`, `protected`, `private`

#### Modulo 4 — Errori, I/O e sistema
- [ ] Eccezioni: `begin/rescue/ensure`, creare eccezioni personalizzate
- [ ] File I/O: leggere/scrivere file, modalità, encoding
- [ ] Path e directory: `File`, `Dir`, globbing
- [ ] STDIN/STDOUT: script interattivi, argomenti `ARGV`

#### Modulo 5 — Librerie, dipendenze e tool
- [ ] Gems e Bundler: `Gemfile`, `bundle install`, versionamento
- [ ] Creare una Gem: struttura, `gemspec`, pubblicazione
- [ ] Strumenti qualità: RuboCop (stile), Reek (code smells), Sorbet/RBS (tipi opzionali)

#### Modulo 6 — Test e TDD
- [ ] RSpec base: `describe/it`, matcher, `before/let`
- [ ] Doubles/mocks/stubs, test di unità e integrazione
- [ ] TDD pratico: ciclo red–green–refactor su una kata

#### Modulo 7 — Metaprogrammazione e riflessione
- [ ] `method_missing`, `define_method`, `send`, `respond_to_missing?`
- [ ] Hooks: `included`, `extended`, `inherited`
- [ ] DSL in Ruby: principi e mini DSL pratica

#### Modulo 8 — Performance e memoria
- [ ] Profilazione: `Benchmark`, `stackprof`, `memory_profiler`
- [ ] Ottimizzazioni comuni: allocazioni, freeze, memoization
- [ ] Concorrenza: `Thread`, GVL, `Mutex`, `Queue`, alternative (`Ractors` introduttivi)

#### Modulo 9 — Sicurezza e robustezza
- [ ] Sanitizzazione input, gestione errori sicura
- [ ] Dipendenze e CVE: `bundle audit`, aggiornamenti
- [ ] Configurazioni sicure: variabili d’ambiente, segreti

#### Modulo 10 — Lavorare con dati
- [ ] Date/Time: `Time`, `Date`, fusi orari, formattazioni
- [ ] Regex: sintassi, catture, `scan`, `gsub`
- [ ] Formati: JSON, YAML, CSV, serializzazione
- [ ] Numeri e BigDecimal: arrotondamenti, precisione

#### Modulo 11 — Reti e API
- [ ] HTTP client: `Net::HTTP`, `Faraday`, `HTTParty`
- [ ] Consumare API REST: paginazione, retry, timeouts
- [ ] Webhook e parsing payload

#### Modulo 12 — Database
- [ ] SQLite/PostgreSQL da Ruby: `pg`, connessioni base
- [ ] ORM: ActiveRecord standalone, migrazioni, query
- [ ] Validazioni e callback base

#### Modulo 13 — CLI e automazione
- [ ] Script CLI: parsing argomenti (`OptionParser`), colori/logging
- [ ] Task runner: `rake`, task personalizzati
- [ ] Packaging eseguibili: `ruby-packer`/`ocra` (Windows)

#### Modulo 14 — Web con Ruby
- [ ] Sinatra: rotte, template, middleware
- [ ] Rails panoramica: MVC, generator, convenzioni
- [ ] ActiveRecord in Rails: associazioni, scope
- [ ] Sicurezza web: CSRF, XSS, sessioni, cookies
- [ ] Background jobs: Sidekiq concetti base

#### Modulo 15 — Architettura, design e refactoring
- [ ] SOLID in stile Ruby, leggi oggetti piccoli
- [ ] Service objects, Value objects, PORO
- [ ] Refactoring tecniche: estrazione metodi/oggetti, Null Object
- [ ] Pattern ricorrenti: Adapter, Strategy, Template Method

#### Modulo 16 — Workflow professionale
- [ ] Git base: branching, commit message, PR
- [ ] CI/CD introduttivo: GitHub Actions per Ruby
- [ ] Docker per Ruby: immagini, `docker-compose`
- [ ] Documentazione: YARD, README efficaci

#### Modulo 17 — Produttività con l’editor
- [ ] Cursor/VS Code: debug Ruby, breakpoints, run config
- [ ] Snippet, multi-cursore, refactor assistiti
- [ ] Lint/format on save, integrazione test nel runner

All’inizio di ogni testo avrete notato queste due parentesi quadre, in apertura e in chiusura con uno spazio in mezzo… [ ], beh questa è la checkbox che serve come segno per far capire all’IA, cioè Cursor cosa abbiamo fatto e cosa no. Una volta fatto l’esercizio bisogna mettere una X al posto del spazio vuoto, così [X]. Il file con .md capirà cosa vogliamo fare!

Una volta fatto questo, andiamo con la creazione di un altro file… “.cursorrules”, che ci servirà come “ruolo” per Cursor stesso. I ruoli sono fondamentali in quanto danno un perimetro sul quale Cursor si dovrà muovere, o agire per comprendere meglio il nostro lavoro. All’interno del file .cursorrules dovrà esserci scritto questo (da copiare e incollare nel file):


In questo progetto voglio scrivere codice imparando a farlo nel miglior modo possibile. Il tuo ruolo è quello di insegnante di Ruby.

Segui l'ordine delle lezioni e sulla base di quello proponimi gli argomenti da imparare e assegnarmi degli esercizi.

Sono a completamente a digiuno di programmazione.

Nel file "scaletta.md" trovi il programma dettagliato del corso. Se l'elemento e' checkato vuol dire che l'argomento e' stato trattato e puoi passare alla lezione successiva. 

In ogni chat ci concentreremo su una singola lezione. Quando la lezione finisce, apriro' una nuova chat. 

Per ogni lezione creero' un file, come "lezione_01.md", etc.

Dentro “lezione_01.md” si inizierà il corso vero e proprio. Anche quest’ultimo file è da creare: lezione_01.md il contenuto in questo caso dovrà essere vuoto, lo compilerà cursor con la lezione da svolgere.

---

Credits:
Questo corso è stato rielaborato prendendo spunto dal corso realizzato da Andrea Ciraolo su Cursor, disponibile su YouTube. Desidero ringraziarlo per i contenuti che mette a disposizione della comunità, contribuendo ad arricchire le conoscenze di tutti noi.
