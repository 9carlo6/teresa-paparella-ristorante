# Teresa Paparella Ristorante — Landing page

Landing page statica pronta per GitHub Pages.

## File
- `index.html`
- `styles.css`
- `assets/` con i due loghi
- `CNAME` con `teresapaparellaristorante.it`
- `.nojekyll`

## Pubblicazione con GitHub Pages
1. Crea un repository pubblico su GitHub, ad esempio `teresa-paparella-ristorante`.
2. Carica tutti i file di questa cartella nella root del repository.
3. Vai in **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**.
5. Seleziona branch `main` e cartella `/(root)`, quindi salva.
6. Attendi il primo deploy.
7. In **Settings → Pages → Custom domain**, verifica che sia impostato `teresapaparellaristorante.it`.
8. Configura i DNS del dominio Aruba verso GitHub Pages.

## DNS GitHub Pages per dominio principale
Aggiungi quattro record A per `@`:
- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Per `www`, aggiungi un record CNAME verso:
- `TUO-USERNAME.github.io`

Dopo la propagazione DNS, abilita **Enforce HTTPS** in GitHub Pages.
