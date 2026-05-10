# Northwind Redux

React öğrenmek için hazırlanmış bir **Northwind** e-ticaret örnek projesi. Projede React, Redux, React Router ve Reactstrap kullanıldı.

## Özellikler

- Kategori listeleme
- Ürün listeleme ve detay sayfası
- Ürün ekleme / güncelleme
- Sepet yönetimi
- Redux tabanlı global state yönetimi

## Kurulum

```bash
npm install
```

## Geliştirme ortamında çalıştırma

```bash
npm start
```

Tarayıcıda şu adres açılır:

```text
http://localhost:3000
```

## Production build

```bash
npm run build
```

## GitHub'a yüklemek için

Repo içinde zaten `.git` bulunuyor. İlk kez GitHub'a göndermek için genel akış:

```bash
git status
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADIN/REPO_ADI.git
git push -u origin main
```

Eğer GitHub Desktop veya JetBrains IDE kullanıyorsan aynı işlemleri arayüzden de yapabilirsin.

## Notlar

- `build/` ve `node_modules/` GitHub'a eklenmemelidir.
- Proje şu anda production build alabiliyor; sadece ESLint uyarıları var.
