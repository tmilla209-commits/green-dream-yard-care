# Green Dream Yard Care 🌿

> *Where your Green Dreams take root.*

The official website for **Green Dream Yard Care** — a family-owned yard care business based in Prairie Grove, AR, serving Lincoln, Prairie Grove, Farmington, and Fayetteville.

- **Owner:** Robert Schumacher
- **Phone:** (209) 559-6862
- **Email:** rschumacher2781@gmail.com

---

## 🚀 To Deploy This Site

👉 **Open [`DEPLOY.md`](./DEPLOY.md)** — step-by-step guide, no terminal required, takes about 5 minutes.

---

## 📁 What's in This Folder

```
.
├── index.html      ← The entire website (HTML + CSS + JS + SVG logo in one file)
├── README.md       ← This file (overview)
├── DEPLOY.md       ← Step-by-step deployment guide
├── deploy.sh       ← One-command updater (for after you've deployed)
└── .gitignore      ← Tells git to ignore OS junk files
```

No build tools, no dependencies, no `npm install`. It's one HTML file that will keep working for years.

---

## 🛠 Editing the Site

Open `index.html` in any text editor (Notepad, VS Code, TextEdit — anything). Find and edit:

| To change... | Search for... |
|---|---|
| Phone number | `(209) 559-6862` and `+12095596862` |
| Email recipient (form) | `rschumacher2781@gmail.com` |
| Slogan / tagline | `Where your Green Dreams` |
| Services offered | The `<!-- ===== SERVICES ===== -->` section |
| Service area cities | `<span class="town-pill">` |
| FAQ questions | The `<!-- ===== FAQ ===== -->` section |
| Business hours | The footer `<h4>Hours</h4>` block |
| Brand colors | Top of the `<style>` block — `:root { --forest: ...; }` |

After saving, push the change to GitHub (see DEPLOY.md → "Making Updates Later"). The live site updates in about 60 seconds.

---

## 📧 How the Booking Form Works

The booking form uses **Formspree** to deliver submissions to Robert's email. You need to set this up once before the form will work.

👉 **Open [`SETUP_FORM.md`](./SETUP_FORM.md)** for the 5-minute setup guide.

Without setup, the form will show an error when submitted. Once set up, every booking emails Robert directly at `rschumacher2781@gmail.com` with all the customer's details.

---

## ✅ Pre-Launch Checklist

- [x] Owner name, phone, email integrated
- [x] Custom logo built and embedded as favicon
- [x] All 4 service cities listed (Lincoln, Prairie Grove, Farmington, Fayetteville)
- [x] Mobile responsive
- [x] Floating call/text buttons for mobile
- [x] Site deployed to Vercel
- [ ] **Set up Formspree for the booking form** (see SETUP_FORM.md — required!)
- [ ] Test booking form on a phone
- [ ] Test "Call Now" buttons on a phone
- [ ] Decide on a custom domain (optional, ~$10/year)
- [ ] Add a free Google Business Profile (huge for local search visibility)

---

## 💡 Future Improvements (When Ready)

When Robert has happy customers, ask permission to add **real testimonials** with first names + town (e.g., "Jen K., Farmington"). A 3-card testimonial section between the Promise and Service Area sections would be a strong addition — let me know and I'll wire it in.

If/when Robert carries liability insurance, we can add an "Insured & bonded" promise card alongside the others.

---

Built with care for Robert. 🌱
