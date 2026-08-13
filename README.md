# Vedakesh — Website Files

This folder contains your complete website:

```
index.html        ← the website itself (must stay named exactly "index.html")
assets/            ← all product photos, logo, and payment QR code
README.md          ← this file
```

Both `index.html` and the `assets` folder must be uploaded together and kept
in the same relative position, or the images on the site won't load.

---

## Publish it for free with GitHub Pages

You don't need to know how to code. Follow these steps exactly.

### 1. Create a GitHub account
Go to [github.com](https://github.com) and sign up (skip if you already have one).

### 2. Create a new repository
- Click the **+** icon (top right) → **New repository**
- Name it something like `vedakesh-website`
- Set it to **Public**
- Do **not** check "Add a README" (you already have one)
- Click **Create repository**

### 3. Upload your files
- On the new repository page, click **"uploading an existing file"**
  (or **Add file → Upload files**)
- Drag in `index.html`, `README.md`, and the whole `assets` folder together
- Scroll down and click **Commit changes**

### 4. Turn on GitHub Pages
- Go to the repository's **Settings** tab
- In the left sidebar, click **Pages**
- Under "Build and deployment" → **Source**, choose **Deploy from a branch**
- Under **Branch**, choose **main** and folder **/(root)**, then **Save**

### 5. Get your live link
- Wait about 1–2 minutes
- Refresh the **Settings → Pages** screen — you'll see:
  `Your site is live at https://YOUR-USERNAME.github.io/vedakesh-website/`
- That's your real, working website link. Share it anywhere — Instagram bio,
  WhatsApp Business, Google Business Profile, etc.

### 6. Making changes later
Whenever you want to update a price, photo, or text:
- Open the file on GitHub (click `index.html` → pencil/edit icon)
- Make your edit → **Commit changes**
- The live site updates automatically within a minute — no re-upload needed

---

## Optional: use your own domain (e.g. www.vedakesh.in)

1. Buy a domain from any registrar (GoDaddy, Namecheap, Hostinger, etc.)
2. In the registrar's DNS settings, add a **CNAME** record pointing to
   `YOUR-USERNAME.github.io`
3. In your repo's **Settings → Pages → Custom domain**, enter your domain
   and save
4. Wait for DNS to propagate (can take a few hours) — GitHub will auto-issue
   a free HTTPS certificate

---

## How orders work on this site (no backend needed)

This is a fully static website — there's no server, database, or payment
gateway integration, which is exactly why it can be hosted for free on
GitHub Pages. The order flow works like this:

1. Customer adds products to cart and fills in name, phone, and address
2. They scan the GPay QR code shown at checkout and pay via any UPI app
3. Tapping **"Send Payment Screenshot on WhatsApp"** opens WhatsApp with
   the full order pre-filled, so they just attach the screenshot and send
4. You confirm and fulfil the order manually from WhatsApp

Because everything (cart, pricing, totals) runs in the customer's browser,
double-check the order details they send you on WhatsApp before shipping —
there's no server-side record of the order beyond that message.
