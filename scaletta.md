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