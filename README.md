# AWS Cloud Clubs Summit — Kayıt Formu

AWS Cloud Clubs İstanbul Okan Üniversitesi zirvesi için katılımcı kayıt formu.

🌐 **Canlı:** <https://kayit.awsccokan.com>

## Özellikler

- Alanlar: ad soyad, e-posta, telefon, üniversite, bölüm, sınıf, AWS deneyimi, LinkedIn, katılım nedeni
- İstemci tarafı doğrulama
- Kayıtlar AWS API Gateway üzerindeki `/register` uç noktasına gönderilir (backend bu repoda değil)

## Teknoloji

React 18 + Vite. GitHub Actions ile GitHub Pages'e yayınlanır.

## Geliştirme

```sh
npm install
npm run dev
npm run build
```

`main` dalına yapılan push `.github/workflows/deploy.yml` ile otomatik yayınlanır.
