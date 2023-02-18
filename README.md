### Installazione

Digitare da terminale questo comandoo:

`npm init`

Seguire l'installazione guidata andando a sovrascrivere o meno i parametri di dafault.

Modificare l'importazione per lo standard ES6:
    - aggiungere nel file package.json `"type": "module"`

## Nodemon

Dopo aver installato Nodemon con il comando `npm install --save-dev nodemon`, andare nel file package.json e ngli *scripts* aggiungere `"start": "nodemon index.js"`; successivamente da terminale lanciare il comando `npm start` (in questo modo qualsiasi variazione che andremo a fare nel file index.js verrà immediatamente riportata nel terminale in tempo reale senza dover lanciare in continuazione il comando `node index.js`).# esempio-node
# esempio-node
