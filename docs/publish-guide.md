# Publish Guide

This project is built for GitHub Pages.

## Local preview

Open `index.html` directly in your browser.

## Push flow

```bash
git init
git add .
git commit -m "Initial Magisk APK Notes site"
git branch -M main
git remote add origin https://github.com/ZeshanAliKhan/magisk-apk-notes-site.git
git push -u origin main
```

## GitHub Pages settings

1. Open repository `Settings`
2. Open `Pages`
3. Choose `Deploy from a branch`
4. Select `main`
5. Select `/root`
6. Save

Expected live URL:

`https://zeshanalikhan.github.io/magisk-apk-notes-site/`
