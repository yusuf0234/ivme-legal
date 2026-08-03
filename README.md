# İvme — yasal sayfalar (GitHub Pages)

Bu klasör **yalnızca** mağaza gizlilik / koşullar sayfalarını içerir.
Ana Flutter projesini public repo’ya koymayın.

## Play Console URL

Yayın sonrası (repo adı `ivme-legal` varsayımı):

```
https://yusuf0234.github.io/ivme-legal/privacy.html
```

## Yayın (ilk kurulum)

1. GitHub’da **public** boş repo oluştur:  
   https://github.com/new?name=ivme-legal&visibility=public  
   (README / .gitignore / license ekleme)
2. Bu klasör zaten commit’li; remote hazır. Terminal:

```bash
cd H:\kpss_yeni\site
git push -u origin main
```

3. Repo → **Settings → Pages** → Source: Deploy from a branch → `main` / `/` (root) → Save
4. ~1 dk sonra Play’e yapıştır:

```
https://yusuf0234.github.io/ivme-legal/privacy.html
```

Kullanıcı adın farklıysa: `git remote set-url origin https://github.com/<USER>/ivme-legal.git`
