# ExpressJS Example App

Questo è un semplice esempio di applicazione ExpressJS che dimostra l'uso dei metodi HTTP di base: GET, POST, PUT, PATCH e DELETE.

## Requisiti

- Node.js
- NPM o Yarn

## Installazione

1. Clona questo repository:
   ```sh
   git clone <URL_DEL_REPOSITORY>

   
Naviga nella cartella del progetto:

cd nome-del-progetto


Installa le dipendenze:

npm install
# o con Yarn
yarn install


Utilizzo
Per avviare l'applicazione, esegui il seguente comando nella root del progetto:

npm start
# o con Yarn
yarn start


L'applicazione sarà ora in esecuzione su http://localhost:3000.

Endpoint
L'applicazione espone i seguenti endpoint:

GET /: Ritorna un messaggio di benvenuto in HTML.
POST /register: Registra un nuovo utente e ritorna un status 201.
PUT /user/dom: Aggiorna le informazioni dell'utente "dom" e ritorna un status 200.
PATCH /user/dom: Modifica parzialmente le informazioni dell'utente "dom" e ritorna un status 200.
DELETE /user/dom: Elimina l'utente "dom" e ritorna un status 200.
Contribuzione
Le Pull Request sono benvenute. Per cambiamenti importanti, apri prima un'issue per discutere cosa vorresti cambiare.
