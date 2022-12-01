# SQL_DB-StoredProcedure

*La Stored-Procedure DBControlsImpiegato può essere ottimizzata.*

Così come è stata scritta, anche nel caso di una direttiva 'delete', è necessario valorizzare tutti i parametri per eseguire correttamente la procedura.
Inoltre bisognerebbe chiaramente conoscere in anticipo le direttive accettabili come valore del parametro: 'update','delete'. Ma in ottica di attivare la
procedura da una pagina web via codice, ciò non è più un problema poichè il valore del parametro sarà vincolato al click di un bottone 
o alla selezione di un <select> HTML.
