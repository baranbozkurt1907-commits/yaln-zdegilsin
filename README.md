# yaln-zdegilsin

## Yayınlama

Bu repo için basit bir GitHub Pages dağıtımı hazırlandı. Oluşturduğum dosyalar:

- `site/index.html` — Web sitesi içeriği
- `site/.nojekyll` — GitHub Pages için
- `.github/workflows/deploy.yml` — Push sonrası otomatik deploy iş akışı

Nasıl yayınlanır:

1. Değişiklikleri commit ve push edin:

```
git add .
git commit -m "Add site and deploy workflow"
git push origin main
```

2. Push sonrası GitHub Actions çalışacak ve `site` klasörünü GitHub Pages üzerinde yayınlayacaktır.

3. Yayın URL'si genellikle `https://<kullanici-adi>.github.io/<repo-adi>/` şeklindedir. GitHub repo ayarlarından Pages bölümünü kontrol edin.

Eğer isterseniz, sizin için commit ve push işlemlerini yapabilirim (git kimlik bilgileri gerekli).
