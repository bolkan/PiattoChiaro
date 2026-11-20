# Piatto Chiaro

Web app statica per consultare il piano alimentare settimanale: cinque pasti al giorno, ricette, alternative previste, guida a pesi ed equivalenze e lista della spesa.

## Avvio
Apri il sito di GitHub Pages. Su iPhone, in Safari, tocca **Condividi → Aggiungi alla schermata Home**. L'app è utilizzabile offline dopo il primo caricamento completo.

## Caratteristiche
- Sette giorni consultabili, con il giorno corrente selezionato automaticamente.
- Alternative e ricette del piano consegnato.
- Lista della spesa per giorno o settimana in base alle scelte.
- Preferenze e pasti spuntati conservati localmente sul dispositivo.
- Nessun account, database, dato sanitario o identificativo.

## Pubblicazione
Il sito è pubblicato dalla root del repository. Un workflow GitHub Actions tenta di distribuirlo automaticamente. Se GitHub Pages non è attivo, vai in Settings → Pages → Source e seleziona **GitHub Actions**.

URL previsto: https://bolkan.github.io/PiattoChiaro/

## Nota
Le trascrizioni servono solo per consultazione e non sostituiscono il piano originale del nutrizionista. In caso di difformità fanno fede i documenti originali e le indicazioni cliniche. Il repository è pubblico: non aggiungere nomi, dati clinici o documenti sanitari.

L'app è autonoma: index.html contiene stile, dati e logica; manifest.webmanifest e sw.js servono per l'installazione e la lettura offline.
