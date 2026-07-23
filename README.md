# Calm Nerves Therapy — Website Files

This folder contains everything needed to publish your site with GitHub Pages (free hosting).

## What's inside
- `index.html` — the whole website (one file: content + styling + animation)
- `assets/therapist.jpg` — your photo, already linked from the homepage
- `.nojekyll` — tells GitHub Pages to serve the files exactly as-is

## How to publish it — step by step

### 1. Create a GitHub account (skip if you have one)
Go to https://github.com/join and sign up for free.

### 2. Create a new repository
- Click the **+** icon (top right) → **New repository**
- Repository name: `calmnervestherapy`
- Set it to **Public**
- Do **not** add a README, .gitignore, or license (you already have these files)
- Click **Create repository**

### 3. Upload these files
- On the new repo's page, click **"uploading an existing file"**
- Drag in `index.html`, `.nojekyll`, and the whole `assets` folder
- Scroll down, click **Commit changes**

### 4. Turn on GitHub Pages
- In your repo, go to **Settings → Pages**
- Under "Build and deployment" → Source, choose **Deploy from a branch**
- Branch: `main`, folder: `/ (root)` → **Save**
- Wait 1–2 minutes, then GitHub shows your live link at the top of that page

### 5. Your website address
Because GitHub Pages builds the address from your **GitHub username** + **repository name**, the link will look like:

```
https://YOUR-USERNAME.github.io/calmnervestherapy/
```

**To get a link that starts exactly with `calmnervestherapy`, you have two real options:**

**Option A — free subdomain, exact match**
Create your GitHub account with the username `calmnervestherapy` itself (if it's still available), then name the repository `calmnervestherapy.github.io` exactly. GitHub Pages then publishes it at:
```
https://calmnervestherapy.github.io
```
This is the only way to get that exact address for free — GitHub Pages URLs are always tied to an account or repo name.

**Option B — your own domain (small yearly cost, most professional)**
1. Buy `calmnervestherapy.com` from a registrar (Namecheap, GoDaddy, Google Domains) — typically €10–15/year.
2. In your repo, add a file named `CNAME` (no extension) containing exactly:
   ```
   calmnervestherapy.com
   ```
3. At your domain registrar, add these DNS records pointing to GitHub Pages:
   - A records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - CNAME record for `www` → `YOUR-USERNAME.github.io`
4. Back in **Settings → Pages**, enter `calmnervestherapy.com` as your custom domain and enable **Enforce HTTPS**.

Hosting itself stays completely free either way — only Option B has the small domain cost.

## Before you publish — please personalize
Open `index.html` and update:
- Your real first/last name (currently shows "Ahmed", guessed from your email)
- Your actual license/qualifying body and license number
- Your therapeutic approach/credentials paragraph in the "About" section

Look for the sections marked with `Edit note:` — they show exactly what to change.
