# Prossime versioni

### Versione 5.8.0-RC (2020-05-07)

+ (Requirement) 7002 - Ora viene restituito un diagnostico separato se la richiesta è ancora da elaborare (issue: [https://github.com/italia/anpr/issues/1706](https://github.com/italia/anpr/issues/1706))
    + In precedenza il 7002 restituiva l'esito EN122 (nessun risultato trovato) anche se la richiesta era ancora in elaborazione. Ora viene restituito anche un apposito diagnostico se la richiesta è ancora in elaborazione.

+ (Requirement) Web - Estensione elenco operazioni soggetto (issue: [https://github.com/italia/anpr/issues/1074](https://github.com/italia/anpr/issues/1074))
    + Nell'applicazione web vengono incluse nell'elenco operazioni anche quelle che riguardano esclusivamente i dati della scheda famiglia (es. motivo costituzione, id famiglia attribuito dal comune). Tali operazioni, non visualizzate nella lista nella versione precedente, possono essere bloccanti ai fini degli annullamenti.

### Versione 5.9.0-RC (2020-05-28)

+ (Requirement) WS [3003/3007] - estensione elenco operazioni soggetto
    + Nel WS 3003/3007 viene data la possibilità tramite apposito parametro di includere nell'elenco operazioni anche quelle che riguardano esclusivamente i dati della scheda famiglia (es. motivo costituzione, id famiglia attribuito dal comune). Tali operazioni, non visualizzate nella lista nella versione precedente, possono essere bloccanti ai fini degli annullamenti.


# Roadmap

+ (Requirement) Accesso tramite CIE/CNS/SPID
    + Accesso all'applicazione InterrogazioneCittadino, per la consultazione dei propri dati, con CNS,CIE e credenziali SPID.

