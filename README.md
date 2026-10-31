# G. VERNIERS — holding & management

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `gverniers.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/gverniers.mjs`).
> To change the content, edit that file and run `node build.mjs gverniers` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@gverniers.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Negotiated / $Documented fee / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are G. VERNIERS, a holding company based in Sint-Niklaas in East Flanders, active since 2008. We hold participations in companies on our own account and we provide management and governance support to them, including involvement in day-to-day management and representation based on the shareholdings we hold. Because the word holding attracts a particular kind of approach, two things are worth stating plainly. We are not an investment firm: we do not manage money for anyone else, we do not offer investment services, we do not solicit funds from the public, and we hold no authorisation from the FSMA to do any of those things. And where we charge management fees to a company we hold, those fees correspond to services actually rendered at a price that can be defended, because fees without substance are disallowed and the correction falls on both companies. Site: gverniers.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
