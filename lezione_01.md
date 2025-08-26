### Lezione 01 — Setup: installare Ruby su Windows e primi passi

Obiettivi della lezione
- Capire cos’è Ruby e dove verrà eseguito sul tuo PC
- Installare Ruby su Windows con RubyInstaller (x64)
- Verificare l’installazione: ruby, gem, irb
- Eseguire il primo script Ruby e usare la console interattiva

Prerequisiti
- PC Windows 10/11 con permessi da amministratore
- Connessione internet

1) Installazione di Ruby (Windows, consigliato Ruby 3.3.x 64‑bit)
1. Vai su `https://rubyinstaller.org/downloads/`.
2. Scarica “Ruby+Devkit 3.3.x-1 (x64)”.
3. Avvia l’installer:
   - Se richiesto, lascia attiva l’opzione “MSYS2 development toolchain”.
   - Al termine, comparirà una finestra per completare MSYS2: scegli l’opzione predefinita (Installazione raccomandata) e attendi che finisca.

2) Verifica dell’installazione
Apri PowerShell e verifica le versioni:
```powershell
ruby -v
gem -v
irb --version
```
Se vedi numeri di versione (es. `ruby 3.3.x`), tutto ok.

Suggerimento charset (facoltativo)
- Per evitare problemi con gli accenti in console: in PowerShell esegui `chcp 65001` prima di lanciare comandi Ruby.

3) Primo script: “Hello, Ruby!”
1. Crea una cartella di lavoro, ad esempio `C:\Users\\<nome>\\Documents\\ruby_sandbox`.
2. Crea un file `hello.rb` con questo contenuto:
```ruby
puts "Ciao dal mio primo script Ruby!"
```
3. Esegui lo script da PowerShell nella cartella dove si trova il file:
```powershell
ruby hello.rb
```

4) Console interattiva (irb)
`irb` è una REPL: puoi provare Ruby riga per riga.
```powershell
irb
```
Prova alcuni comandi:
```ruby
2 + 3
"Ruby".upcase
"7".to_i + 5
name = "Anna"; "Ciao, #{name}!"
```
Per uscire da irb: digita `exit` e premi Invio.

5) Gestione versioni (opzionale, solo panoramica)
Su Windows, quando avrai bisogno di più versioni di Ruby, potrai valutare strumenti come “uru”. Per ora non è necessario: concentrati sull’uso di Ruby 3.3.

Verifica rapida
- Vedi versioni con `ruby -v`, `gem -v`, `irb --version`? ✔️
- `ruby hello.rb` stampa il messaggio? ✔️
- In `irb`, le espressioni restituiscono il risultato atteso? ✔️

Esercizi
1. Input e saluto
   - Crea `greet.rb` che chieda il nome all’utente e stampi “Ciao, <nome>!”. Suggerimento: `gets.chomp` legge una riga da tastiera.
   - Esegui con `ruby greet.rb` e prova più nomi.

2. Somma due numeri
   - Crea `sum.rb` che chieda due numeri e stampi la loro somma.
   - Ricorda di convertire l’input: `to_i` o `to_f`.

3. Tabellina breve
   - Crea `times.rb` che dato un numero `n` stampi i risultati di `n * 1` fino a `n * 10`.

4. Bonus (facoltativo)
   - In `irb`, prova metodi su stringhe: `downcase`, `capitalize`, `length`.
   - Prova qualche operazione con numeri: `**` (potenza), `%` (modulo).

Troubleshooting
- Se `ruby` non è riconosciuto: chiudi e riapri PowerShell, oppure riavvia il PC (serve aggiornare il PATH). In caso estremo, reinstalla con RubyInstaller assicurandoti di spuntare l’opzione per MSYS2 Devkit.
- Se i caratteri accentati non si vedono bene: esegui `chcp 65001` prima di lanciare gli script o usa Windows Terminal impostando UTF‑8.

Prossimi passi
- Nella prossima lezione inizieremo la sintassi base di Ruby: variabili, tipi primitivi e operatori.


