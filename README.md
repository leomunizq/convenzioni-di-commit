<h1 align="center">
📄<br>Modelli di Commit
</h1>

Secondo la documentazione di Conventional Commits, i commit semantici sono una semplice convenzione da utilizzare nei messaggi di commit.

Questa convenzione stabilisce un insieme di regole per creare un registro dei commit esplicito, che facilita la creazione di strumenti automatizzati.

Questi commit aiuteranno te e il tuo team a capire facilmente quali modifiche sono state apportate alla sezione di codice che è stata committata.

Questa identificazione avviene attraverso una parola e un'emoji che identifica se quel commit riguarda una modifica del codice, un aggiornamento dei pacchetti, la documentazione, una modifica visuale, un test...


## 🦄 Tipo e Descrizione
Il commit semantico ha i seguenti elementi strutturali (tipi), che indicano l'intenzione del tuo commit all'utilizzatore del tuo codice.

- `feat`- I commit di tipo feat indicano che il pezzo di codice include una **nuova funzionalità**, (relativa al MINOR del versioning semantico).

-  `fix` - I commit di tipo fix indicano che il pezzo di codice committato è una **correzione di bug**, (correlata alla PATCH del versioning semantico).

-  `docs` - I commit di tipo docs indicano che ci sono state **modifiche alla documentazione**, per esempio nel Readme del repository (non include modifiche al codice).

-  `test` - I commit di tipo test sono utilizzati quando vengono effettuate **modifiche ai test**, sia creando, modificando o eliminando test unitari. (Non include modifiche al codice)

- `build` - I commit di tipo build sono utilizzati quando vengono effettuate **modifiche a file di build e dipendenze**.

-  `perf` - I commit di tipo perf servono per identificare eventuali modifiche al codice che **riguardano la performance.**

-  `style` -  I commit di tipo style indicano che sono state apportate modifiche a **formati del codice**, punti e virgola, spazi intermedi, lint... (non include modifiche al codice). (non include modifiche al codice).

- `refactor` - I commit di tipo refactor si riferiscono a modifiche dovute a un **refactoring che non cambia la funzionalità**, ad esempio un cambiamento nel modo in cui viene resa una certa parte dello schermo, ma che ha mantenuto la stessa funzionalità, o miglioramenti delle prestazioni dovuti a una revisione del codice.

- `chore` - I commit di tipo chore indicano **aggiornamenti di task di compilazione**, impostazioni dell'amministratore, pacchetti... come l'aggiunta di un pacchetto a gitignore.

- `ci` - I commit di tipo ci indicano modifiche relative a **integrazione continua**.



## 💡 Raccomandazioni

- Aggiungere un titolo coerente con il titolo del contenuto;
- Si raccomanda che la prima riga non sia più lunga di 4 parole;
- Per descrivere in dettaglio, usare la descrizione del commit;
- Utilizzare un emoji all'inizio del messaggio di commit che rappresenti il commit;
- Un link deve essere aggiunto nella sua forma più autentica, cioè senza accorciatori di link e link affiliati;

## 🍧 Commits Complements

- **Footer:** Di solito un'informazione sul revisore e il numero di card di trello o jira 
  Esempio: Reviewed-by: Angelo Bertozzi Refs #133
- Body: descrizioni più precise di ciò che è contenuto nel commit, presentando gli impatti e le ragioni per cui sono state apportate le modifiche al codice, nonché le istruzioni essenziali per gli interventi futuri. 
  Esempio: see the issue for details on typos fixed.
- Descrizioni**: una breve descrizione della modifica.
  Esempio: correct minor typos in code


## 💈 Padrões de emojis

<table>
  <thead>
    <tr>
      <th>Tipo di commit</th>
      <th>Emojis</th>
      <th>Parola chiave</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Accessibilità</td>
      <td>♿ <code>:wheelchair:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Aggiunta di un test</td>
      <td>✅ <code>:white_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Aggiunta di una dipendenza</td>
      <td>➕ <code>:heavy_plus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Modifiche di revisione del codice</td>
      <td>👌 <code>:ok_hand:</code></td>
      <td><code>style</code></td>
    </tr>
    <tr>
      <td>Animazioni e transizioni</td>
      <td>💫 <code>:dizzy:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td>🐛 <code>:bug:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Commenti</td>
      <td>💡 <code>:bulb:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Primo commit</td>
      <td>🎉 <code>:tada:</code></td>
      <td><code>init</code></td>
    </tr>
    <tr>
      <td>Configurazione</td>
      <td>🔧 <code>:wrench:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Deploy</td>
      <td>🚀 <code>:rocket:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Documentazione</td>
      <td>📚 <code>:books:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>In corso</td>
      <td>🚧 <code>:construction:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Stilizzazione dell'interfaccia</td>
      <td>💄 <code>:lipstick:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Infrastruttura</td>
      <td>🧱 <code>:bricks:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>Elenco di idee (tasks)</td>
      <td>🔜 <code> :soon: </code></td>
      <td></td>
    </tr>
    <tr>
      <td>Spostare/Rinominare</td>
      <td>🚚 <code>:truck:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Nuova funzionalità</td>
      <td>✨ <code>:sparkles:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Package.json in JS</td>
      <td>📦 <code>:package:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Prestazioni</td>
      <td>⚡ <code>:zap:</code></td>
      <td><code>perf</code></td>
    </tr>
    <tr>
        <td>Rifattorizzazione</td>
        <td>♻️ <code>:recycle:</code></td>
        <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Rimozione di un file</td>
      <td>🔥 <code>:fire:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Rimozione di una dipendenza</td>
      <td>➖ <code>:heavy_minus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Reattività</td>
      <td>📱 <code>:iphone:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Revertire le modifiche</td>
      <td>💥 <code>:boom:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Sicurezza</td>
      <td>🔒️ <code>:lock:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td>🔍️ <code>:mag:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tag di versione</td>
      <td>🔖 <code>:bookmark:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Test di approvazione</td>
      <td>✔️ <code>:heavy_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Test</td>
      <td>🧪 <code>:test_tube:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Testo</td>
      <td>📝 <code>:pencil:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tipizzazione</td>
      <td>🏷️ <code>:label:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Gestione degli errori</td>
      <td>🥅 <code>:goal_net:</code></td>
      <td></td>
    </tr>
  </tbody>
</table>

## 💻 Exemplos

<table>
  <thead>
    <tr>
      <th>Comando git</th>
      <th>Risultato su GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m ":tada: Commit iniziale"</code>
      </td>
      <td>🎉 Commit iniziale</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":books: docs: Aggiornamento del README"</code>
      </td>
      <td>📚 docs: Aggiornamento del README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Loop infinito alla riga 50"</code>
      </td>
      <td>🐛 fix: Loop infinito alla riga 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Pagina di login"</code>
      </td>
      <td>✨ feat: Pagina di login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modifica in Dockerfile"</code>
      </td>
      <td>🧱 ci: Modifica in Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Conversione in arrow functions"</code>
      </td>
      <td>♻️ refactor: Conversione in arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Miglioramento del tempo di risposta"</code>
      </td>
      <td>⚡ perf: Miglioramento del tempo di risposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Revertendo modifiche inefficienti"</code>
      </td>
      <td>💥 fix: Revertendo modifiche inefficienti</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Stilizzazione CSS del modulo"</code>
      </td>
      <td>💄 feat: Stilizzazione CSS del modulo</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: test: Creazione di un nuovo test"</code>
      </td>
      <td>🧪 test: Creazione di un nuovo test</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bulb: docs: Commenti sulla funzione LoremIpsum( )"</code>
      </td>
      <td>💡 docs: Commenti sulla funzione LoremIpsum( )</td>
    </tr>
  </tbody>
</table>
