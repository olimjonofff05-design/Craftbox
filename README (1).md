# Craftbox — Creator Toolkit

Invoice Generator, CV Builder, QR Code Generator va Social Post Designer — bitta sahifada, faqat brauzerda ishlaydi (server kerak emas).

## GitHub'ga joylash

Repo allaqachon ochilgan: `https://github.com/olimjonofff05-design/Craftbox.git`

Terminalda (yoki Git Bash'da) shu papkada quyidagilarni bajaring:

```bash
git init
git remote add origin https://github.com/olimjonofff05-design/Craftbox.git
git add .
git commit -m "Craftbox: invoice, CV, QR va social post generator"
git branch -M main
git push -u origin main
```

Agar repo'da avval biror narsa bo'lsa (masalan README), quyidagini oldin bajaring:

```bash
git pull origin main --allow-unrelated-histories
```

so'ng qayta `git push -u origin main`.

## Bepul hosting — GitHub Pages

Push qilingandan keyin saytni bepul onlayn qilish uchun:

1. Repo sahifasida **Settings → Pages** ga o'ting
2. "Build and deployment" bo'limida **Source: Deploy from a branch** ni tanlang
3. Branch: **main**, Folder: **/ (root)** — Save bosing
4. 1–2 daqiqadan so'ng sayt shu manzilda ishga tushadi:

```
https://olimjonofff05-design.github.io/Craftbox/
```

`index.html` fayli allaqachon papkada bor — GitHub Pages avtomatik uni bosh sahifa qilib oladi, qo'shimcha sozlash kerak emas.

## Fayllar

- `index.html` — to'liq ilova (HTML + CSS + JS, bitta faylda)
- `README.md` — shu qo'llanma
