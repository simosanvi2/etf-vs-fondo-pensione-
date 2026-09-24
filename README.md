# ETF vs Fondo Pensione

Simulatore interattivo (HTML + Chart.js) che confronta un piano di accumulo in un ETF azionario globale con un fondo pensione italiano, applicando la fiscalità italiana.

Apri `index.html` in un browser: non serve alcuna installazione (Chart.js e i font sono caricati da CDN).

## Cosa modella

| Voce | ETF | Fondo pensione |
|---|---|---|
| Tassazione dei rendimenti | 26% sulla plusvalenza al momento della vendita | 20% annuo sul rendimento maturato (12,5% sulla quota in titoli di Stato), con credito per le perdite |
| Imposta di bollo | 0,2% annuo sul controvalore, pagato dal conto (le quote restano investite, il bollo è sottratto dal netto) oppure vendendo quote (con tassazione immediata della plusvalenza realizzata) | Esente |
| Versamenti | Nessun beneficio | Deducibili dal reddito fino a 5.164,57 €/anno (contributo del datore incluso); risparmio calcolato su scaglioni IRPEF 2026 o 2025, detrazioni da lavoro dipendente e addizionali |
| Uscita | 26% sulla plusvalenza residua | 15% sui soli contributi dedotti, −0,30 punti per ogni anno di adesione oltre il 15°, minimo 9% |

Il rimborso IRPEF (incassato l'anno successivo) può essere reinvestito in un ETF, versato nel fondo oppure speso. I risultati sono mostrati in euro nominali o in euro di oggi.

## Limiti

Rendimenti costanti, nessun obbligo di rendita sul 50% del montante, nessun TFR, riscatti o anticipazioni, nessun plafond extra per i neoassunti post-2007. Strumento didattico, non consulenza finanziaria.
