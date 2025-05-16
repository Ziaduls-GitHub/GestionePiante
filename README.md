# Progetto di Sistema Informativo per la Gestione dei Semi delle Piante

## Cosa prevede?
Il progetto prevede la realizzazione di un sistema informativo per digitalizzare e ottimizzare la gestione dei semi delle piante all’interno di un centro di conservazione agronomica o di un orto botanico. L’obiettivo è sostituire l’attuale gestione manuale con un’applicazione web intuitiva e completa. Il cuore del sistema sarà un database SQL che ospiterà tutte le informazioni necessarie per monitorare l’intero ciclo di vita dei semi, dalla raccolta alla semina o distribuzione.

Il **database** conterrà un catalogo dettagliato di tutte le varietà di semi raccolte, conservate o acquistate. Ogni seme sarà descritto da informazioni agronomiche fondamentali: specie, varietà, zona di provenienza, data di raccolta, condizioni di conservazione, data di scadenza e stato (es. disponibile, in scadenza, esaurito). Per ogni varietà saranno associati dati sui fornitori o raccoglitori, sulla germinabilità media e sulle condizioni ottimali di conservazione.
Gli utenti del sistema saranno classificati in tre categorie principali: agronomi, tecnici di laboratorio e volontari. Gli agronomi avranno il ruolo di supervisione tecnica e progettazione delle coltivazioni; i tecnici si occuperanno dell’inventario e dei test di germinabilità; i volontari potranno registrare attività di supporto, come la catalogazione o l’impacchettamento dei semi. Ogni utente accederà al sistema con credenziali personalizzate e ruoli differenziati.

La gestione dei lotti di semi sarà una funzionalità chiave dell’applicazione. Per ogni lotto sarà tracciata la sua origine, la quantità disponibile, gli eventuali prelievi o aggiunte, nonché la destinazione (semina, conservazione, distribuzione). Sarà inoltre possibile mantenere uno storico delle analisi effettuate (germinabilità, umidità, contaminazioni).

Il sistema offrirà una sezione dedicata agli eventi agronomici o didattici organizzati dal centro, come laboratori di semina, scambi di semi o corsi sulla biodiversità agricola. Gli utenti potranno consultare il calendario, iscriversi e registrare la partecipazione. Sarà presente anche una sezione informativa per ogni varietà di pianta: note agronomiche, foto, schede tecniche scaricabili. Gli utenti potranno inoltre lasciare osservazioni sulla qualità dei semi utilizzati, facilitando il monitoraggio partecipativo della biodiversità agraria. Il personale permanente del centro sarà gestito tramite un modulo dedicato, che ne descriverà ruoli, responsabilità e competenze, utile per la gestione interna e per facilitare la collaborazione tra i team.

### Obiettivi del Progetto
1. Analisi e progettazione concettuale
Analizzare il dominio del problema e costruire un modello entità-relazione, includendo eventuali ruoli di specializzazione tra utenti (es. agronomi, tecnici, volontari). Il modello includerà entità come Seme, Lotto, Analisi, Evento, Partecipazione, Utente, Ruolo.

2. Progettazione logica
Derivare il modello logico relazionale a partire dal modello E-R, indicando le chiavi primarie, esterne, vincoli di integrità, e giustificando semplificazioni adottate.

3. Implementazione del sistema informativo
Utilizzando Django, realizzare un’applicazione che permetta:

Visualizzazione del catalogo dei semi, con scheda dettagliata.
Registrazione e autenticazione utenti (con ruoli differenziati).
Gestione dei lotti di semi (inserimento, modifica, tracciamento).
Gestione e consultazione delle analisi di laboratorio.
Iscrizione e gestione eventi.
Inserimento e visualizzazione delle osservazioni sugli utilizzi dei semi.
Consultazione schede tecniche per pianta.
Storico delle movimentazioni per ogni lotto.

L’applicazione dovrà essere sviluppata esclusivamente con:
Backend Django,
Template di Django,
Bootstrap CSS per il frontend.

*eventuali funzionalità JavaScript saranno limitate a ciò che è strettamente necessario*.
