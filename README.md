# Lustrum Timer

Aftellen naar 21:35, 22:35, 23:35, 00:35 en 01:35 (26–27 november 2026). Zwart scherm met paarse LED-cijfers. Op 0 staat één minuut lang de tekst van dat uur in beeld.

| Pagina | Voor wie |
|---|---|
| `index.html#CODE` | Beamer-laptop. Klik één keer om te starten, dan gaat het scherm naar volledig scherm. |
| `bediening.html#CODE` | Organisator. Hiermee stel je de teksten in en keur je inzendingen goed. |
| `inzenden.html` | Gasten, via de QR-code op het bord. |

`CODE` is een geheime code die niet in deze repository staat. Zonder de code kan niemand het bord bedienen.

- Inzendingen van gasten komen eerst in de bediening terecht. Na Accepteren verschijnen ze als kaartje rondom de timer, maximaal 20 tegelijk. De rest wacht in de rij. Hoe lang een kaartje blijft staan stel je in de bediening in (standaard 20 s). Alles kun je daar ook weer weghalen.
- Mededelingen van de organisatie zijn paarse kaartjes met "📣 MEDEDELING" en blijven staan tot je ze weghaalt.
- In de laatste 30 seconden voor een moment en tijdens de tekst van het uur staat alleen de grote timer in beeld.
- Testen: `index.html?test#CODE` laat elke 2 minuten een moment afgaan.
- Berichten gaan via ntfy.sh. De timer rekent steeds vanaf de klok van de laptop. Valt het internet weg, dan blijft de timer gewoon lopen.

Sneltoetsen op de laptop: F (tekst van het uur nu tonen), S (stop), T/W (tekst onder de timer zetten of weghalen), Q (QR-code aan/uit), N (inzending van het bord halen), +/- (klok ±1 s), H (hulp).
