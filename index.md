# Indice progetto — Albero Genealogico Famiglia Rinonapoli

Mappa dei file del progetto per orientarsi rapidamente (pensata anche per gli LLM che riprendono il lavoro). Punto di ingresso: parti da qui, poi leggi `PROGETTO-albero-rinonapoli.md`.

## Cos'è il progetto
Sito web interattivo dell'albero genealogico della famiglia Rinonapoli, ricavato da un poster cartaceo. È un **unico file HTML** (HTML+CSS+JS inline), **online** su **https://origini.lucarinonapoli.com** (GitHub Pages + dominio personalizzato).
Autore: Luca Rinonapoli (UX/UI). Ricerca: Filippo Sallusto.

## File nel progetto
| File | Cos'è | Quando leggerlo |
|---|---|---|
| `index.md` | Questo indice: mappa del progetto. | Per primo, per orientarsi. |
| `PROGETTO-albero-rinonapoli.md` | Documentazione completa: obiettivo, stato, pubblicazione, funzionalità, struttura dati (29 persone + id), note tecniche, preferenze. | Sempre, prima di toccare il sito. È il contesto. |
| `albero-rinonapoli.html` | Il sito vero e proprio (unico file). Fonte di verità della versione online. | Quando si legge o modifica il codice. |

## Risorse esterne (non nel progetto)
- **Repo GitHub** (codice + immagini): `https://github.com/lvcar/albero_genealogico`. Il sito online è `index.html` nella root.
- **Ritratti** (29): cartella `images/` della repo, caricati via URL raw `https://raw.githubusercontent.com/lvcar/albero_genealogico/main/images/<id>.webp`. **Non sono allegati al progetto.**
- **Stemma** e **logo alberello**: incorporati in base64 dentro l'HTML (non da URL).
- **Sito live**: `https://origini.lucarinonapoli.com`.

## Come riprendere il lavoro
1. Leggi `PROGETTO-albero-rinonapoli.md` per il contesto completo.
2. Le modifiche si fanno **direttamente** su `albero-rinonapoli.html` (dati nel `<script>` come JSON, stili nel `<style>`). **Mantieni lo stesso nome file.**
3. Per pubblicare: sostituisci `index.html` nella repo con il file aggiornato, poi hard refresh.

## Stato in breve
- Sito online e funzionante (desktop + mobile).
- Pan/zoom con confini (no pan libero stile Figma), modal al click sulle card, modal crediti dal footer.
- Selezione testo disattivata su desktop (area albero); su mobile niente pulsanti +/-, titolo su una riga.

---
*Aggiorna questo indice e `PROGETTO-albero-rinonapoli.md` quando il progetto cambia in modo rilevante.*
