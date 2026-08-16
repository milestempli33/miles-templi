# Cavalerii Templieri — blog de istorie

Site static simplu, fără bază de date, fără server — doar fișiere HTML și CSS.
Se poate deschide direct în browser sau publica gratuit online.

## Structura

```
cavalerii-templieri/
├── index.html              → pagina principală (lista de articole)
├── despre.html              → pagina "Despre"
├── style.css                 → tot stilul vizual al site-ului
└── articole/
    ├── istoria-ordinului-templier.html
    ├── misterele-templierilor.html
    ├── procesul-templierilor-adevarul.html
    └── _model-articol-nou.html   → model de copiat pentru articole noi
```

## Cum adaugi un articol nou

1. În folderul `articole`, copiază fișierul `_model-articol-nou.html`
   și redenumește copia (fără spații/diacritice), ex: `comoara-de-la-rosslyn.html`.
2. Deschide fișierul copiat și înlocuiește textele din `[paranteze pătrate]`.
3. Deschide `index.html`, copiază un bloc `<article class="post-card">...</article>`
   existent și lipește-l deasupra celorlalte, apoi actualizează titlul, textul
   scurt și linkul către noul fișier.
4. Salvează și republică (vezi mai jos).

## Cum vezi site-ul local, înainte de publicare

Deschide pur și simplu `index.html` din folder, dublu-clic — se deschide în
browser și funcționează exact ca online.

## Cum publici gratuit online

Cea mai simplă variantă, fără cont GitHub sau linie de comandă:

**Netlify Drop** (https://app.netlify.com/drop)
1. Intri pe pagină, tragi cu mouse-ul întregul folder `cavalerii-templieri`
   peste zona indicată.
2. În câteva secunde primești un link public (ex: `nume-random.netlify.app`).
3. Poți reveni oricând pe aceeași pagină și trage folderul din nou, cu
   modificările tale, ca să actualizezi site-ul live.

Alternativ, dacă vrei un link fix și ai deja cont GitHub, varianta este
**GitHub Pages**: creezi un repository, urci fișierele, activezi Pages din
Settings → Pages. Spune-mi dacă vrei ajutor pas cu pas pentru asta.
