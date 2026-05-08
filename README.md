# Cadou QR - Plic cu "Te iubesc"

Pagina este în `index.html`.

## 1) Publică pe GitHub Pages

1. Intră pe [github.com](https://github.com) și creează un repository nou (de exemplu `cadou-iubita`).
2. În folderul acestui proiect, rulează în terminal:

```powershell
git init
git add .
git commit -m "Prima versiune"
git branch -M main
git remote add origin https://github.com/USERNAME/cadou-iubita.git
git push -u origin main
```

3. În repository pe GitHub: `Settings` -> `Pages`.
4. La `Source`, alege `Deploy from a branch`.
5. Selectează branch `main` și folder `/ (root)`, apoi `Save`.
6. Așteaptă 1-2 minute. Linkul va fi:

`https://USERNAME.github.io/cadou-iubita/`

## 2) Generează codul QR

1. Copiază linkul de mai sus.
2. Intră pe un generator QR, de exemplu [QR Code Generator](https://www.qr-code-generator.com/) sau [QRCode Monkey](https://www.qrcode-monkey.com/).
3. Lipește linkul, generează QR și descarcă PNG/SVG.
4. Printează codul QR pe foaie.

## 3) Test rapid

- Deschide linkul public.
- Scanează QR-ul cu telefonul.
- Apasă pe plic: se deschide și apare mesajul `Te iubesc!`.
