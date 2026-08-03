# İvme — yasal sayfalar (GitHub Pages)

Bu klasör **yalnızca** mağaza gizlilik / koşullar sayfalarını içerir.
Ana Flutter projesini public repo’ya koymayın.

## Play Console URL

Yayın sonrası (repo adı `ivme-legal` varsayımı):

```
https://<GITHUB_KULLANICI>.github.io/ivme-legal/privacy.html
```

## Yayın (ilk kurulum)

GitHub’da **public** repo oluştur: `ivme-legal` (boş, README’siz).

Sonra bu klasörde:

```bash
cd site
git init
git add .
git commit -m "İvme gizlilik ve kullanım koşulları"
git branch -M main
git remote add origin https://github.com/<GITHUB_KULLANICI>/ivme-legal.git
git push -u origin main
```

GitHub → **Settings → Pages**:

1. Source: **Deploy from a branch**
2. Branch: `main` / **root** (`/`)
3. Save

1–2 dakika sonra URL açılır. Play Console → Gizlilik politikası alanına
`privacy.html` adresini yapıştırın.
