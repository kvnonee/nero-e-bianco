# Nero e Bianco

Tema monocromatico (nero, bianco e grigi) per Discord, con pannelli semi-trasparenti
a effetto vetro e sfondo personalizzabile. Funziona con **BetterDiscord** e **Vencord**.

## Installazione

**BetterDiscord**
1. Scarica `nero-e-bianco.theme.css`.
2. Impostazioni di Discord → Themes → *Open Themes Folder*.
3. Copia il file nella cartella e attiva il tema.

**Vencord**
1. Scarica `nero-e-bianco.theme.css`.
2. Impostazioni → Vencord → Themes → *Open Themes Folder*.
3. Copia il file, premi *Load Missing Themes* e attiva il tema.

## Come mettere il tuo sfondo

Apri il file con un editor di testo e cerca il blocco `IMPOSTAZIONI RAPIDE` in cima.
Sostituisci `none` nella riga `--nb-bg-image` con il link diretto a un'immagine:

```css
--nb-bg-image: url("https://esempio.com/mia-immagine.jpg");
```

Altre opzioni nello stesso blocco:

| Variabile | Cosa fa |
|---|---|
| `--nb-bg-dim` | Scurisce lo sfondo (0 = nitido, 1 = nero) |
| `--nb-blur` | Sfocatura dei pannelli |
| `--nb-bg-position` | Posizione dell'immagine |
| `--nb-accent` | Colore d'accento (default grigio chiaro) |

## Segnalare problemi

Apri una issue su GitHub indicando client (BetterDiscord/Vencord) e uno screenshot.

## Licenza

MIT
