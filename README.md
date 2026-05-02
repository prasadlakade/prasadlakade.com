# Prasad Lakade — Portfolio Website
### Live at: [prasadlakade.com](https://prasadlakade.com)

---

## 🚀 Deploy to GitHub Pages with Custom Domain

Since you already have the `prasadlakade.com` repo on GitHub, follow these steps:

### Step 1: Clone your existing repo & replace files

```bash
git clone https://github.com/prasadlakade/prasadlakade.com.git
cd prasadlakade.com
```

Delete old files and copy in the new portfolio files (index.html, experience.html, CNAME, .github/ folder).

### Step 2: Push to GitHub

```bash
git add .
git commit -m "New portfolio site"
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to → https://github.com/prasadlakade/prasadlakade.com/settings/pages
2. Under **Source**, select **GitHub Actions**
3. The workflow will auto-run and deploy

### Step 4: Configure Custom Domain DNS

In your domain registrar, add these records:

**A Records** (apex domain):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**CNAME** (for www):
```
www  →  prasadlakade.github.io
```

### Step 5: Set custom domain in GitHub

1. Repo → Settings → Pages
2. Under **Custom domain**, enter: `prasadlakade.com`
3. Save → GitHub auto-enables HTTPS

✅ Site live at https://prasadlakade.com
