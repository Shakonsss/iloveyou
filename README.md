# Cadou QR - Plic cu "Te iubesc"

Pagina-cadou este în `p-be922fbccf27/index.html`.

Linkul secret pentru QR:

`https://shakonsss.github.io/iloveyou/p-be922fbccf27/`

Notă: `index.html` din rădăcină este acum o pagină neutră (pentru discreție).

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
6. Așteaptă 1-2 minute.

## 2) Generează codul QR

1. Copiază linkul secret de mai sus.
2. Intră pe un generator QR, de exemplu [QR Code Generator](https://www.qr-code-generator.com/) sau [QRCode Monkey](https://www.qrcode-monkey.com/).
3. Lipește linkul, generează QR și descarcă PNG/SVG.
4. Printează codul QR pe foaie.

## 3) Test rapid

- Deschide linkul secret.
- Scanează QR-ul cu telefonul.
- Apasă pe plic: se deschide și apare mesajul `Te iubesc!`.

## 4) Mod discret (recomandat)

- Pagina include tag-uri `noindex` ca să reducă șansele de indexare.
- După ce oferi cadoul, intră în `Settings` -> `Pages` -> `Unpublish site`.
- După unpublish, poți seta repo-ul înapoi pe `Private`.
