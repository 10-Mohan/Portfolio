# Mohan Kumbar — Portfolio

A single-file static site. No build step, no dependencies to install.

## Deploy in 3 steps (Vercel)

1. Create a new GitHub repo (e.g. `10-Mohan/portfolio`) and push this `index.html` into it
   - `index.html` is in this same folder you downloaded (`mohan-portfolio/index.html`)
   - Easiest: on GitHub, click "Add file → Upload files" and drag `index.html` in directly — no git commands needed
2. Go to https://vercel.com → **Add New Project** → **Import** your `portfolio` repo
3. Leave all settings default → **Deploy**

You'll get a free URL like `portfolio-10-mohan.vercel.app` immediately.

## Connect your mohankumbar.dev domain

1. Buy the domain at Porkbun, Namecheap, or a registrar of your choice
2. In Vercel: **Project → Settings → Domains → Add** → type your domain
3. Vercel will show you DNS records (usually one A record + one CNAME)
4. Go to your registrar's DNS settings and add those exact records
5. Wait for DNS to propagate (10 minutes to a few hours) — then your site is live at your custom domain

## Editing content later

Everything is in `index.html` — search for the section you want to change:
- `id="about"` — your bio
- `id="skills"` — the skill tags
- `id="projects"` — project cards (add new ones by copying a `.project-card` block)
- `id="experience"` — internships and certifications
- `id="contact"` — email/social links

No build tools needed — just edit and re-upload/push the file.
