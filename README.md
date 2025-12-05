# Revi srl - Website

Sito web statico ottimizzato per SEO per Revi srl, centro revisione veicoli a Ragusa.

## Caratteristiche

- ✅ **SEO Ottimizzato**: Ottimizzato per la keyword "Revisione auto Ragusa"
- ✅ **Responsive Design**: Completamente responsive per tutti i dispositivi
- ✅ **Structured Data**: Dati strutturati JSON-LD per migliorare la visibilità su Google
- ✅ **Meta Tags**: Meta tags completi per social media e motori di ricerca
- ✅ **Design Moderno**: Interfaccia moderna e professionale
- ✅ **Performance**: Sito statico veloce e leggero

## Struttura del Progetto

```
ReviWebsite/
├── index.html      # Pagina principale
├── styles.css      # Fogli di stile
└── README.md       # Questo file
```

## SEO Features

### Meta Tags
- Title ottimizzato per "Revisione auto Ragusa"
- Meta description con keyword principale
- Open Graph tags per social media
- Twitter Card tags
- Canonical URL

### Structured Data (JSON-LD)
- Schema.org LocalBusiness
- Informazioni complete dell'azienda
- Coordinate geografiche
- Orari di apertura

### Ottimizzazioni
- Semantic HTML5
- Heading structure ottimizzata
- Alt text per immagini (da aggiungere quando disponibili)
- Internal linking
- Mobile-friendly

## Personalizzazione

### Aggiornare le Informazioni di Contatto

Nel file `index.html`, aggiorna:
- Numero di telefono (attualmente placeholder)
- Orari di apertura se diversi
- Link ai social media se disponibili

### Aggiungere Immagini

1. Crea una cartella `images/`
2. Aggiungi il logo come `logo.png`
3. Aggiorna i percorsi delle immagini nel file HTML

### Google Maps

Il codice iframe per Google Maps è incluso. Per ottenere il link corretto:
1. Vai su Google Maps
2. Cerca l'indirizzo: "Zona ind.le 3°fase Viale 24 n°4, 97100 Ragusa"
3. Clicca su "Condividi" > "Incorpora una mappa"
4. Sostituisci l'attuale iframe src con quello ottenuto

## Deployment

### Opzioni di Hosting

1. **Netlify** (consigliato per siti statici)
   - Drag & drop la cartella
   - Deploy automatico da Git

2. **GitHub Pages**
   - Push su repository GitHub
   - Abilita GitHub Pages nelle impostazioni

3. **Vercel**
   - Connessione a repository Git
   - Deploy automatico

4. **Hosting tradizionale**
   - Carica i file via FTP
   - Assicurati che `index.html` sia nella root

### Dominio

Dopo il deployment, aggiorna:
- Canonical URL in `index.html`
- Open Graph URL
- Twitter Card URL
- Structured Data URL

## Miglioramenti Futuri

- [ ] Aggiungere pagina "Chi Siamo"
- [ ] Aggiungere pagina "Servizi" dettagliata
- [ ] Form di contatto funzionante
- [ ] Galleria immagini
- [ ] Blog/News per contenuti SEO
- [ ] Google Analytics
- [ ] Google Search Console
- [ ] Sitemap.xml
- [ ] robots.txt

## Note

- Il numero di telefono è un placeholder - aggiorna con il numero reale
- Le coordinate GPS sono approssimative - aggiorna con quelle esatte se disponibili
- Il logo e le immagini devono essere aggiunti quando disponibili

## Supporto

Per domande o supporto, contatta lo sviluppatore o consulta la documentazione HTML/CSS standard.
