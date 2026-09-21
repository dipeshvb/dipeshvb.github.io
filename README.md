# dipeshbalani.com

Personal portfolio site. Plain HTML, no build step.

## Update
- Edit `index.html` directly.
- Replace `Dipesh_Balani_Resume.pdf` when the resume changes (keep the same filename).
- Project "Code" links point to github.com/dipeshbalani/<repo-name>. Create repos with those names or edit the links.

## Deploy (GitHub Pages)
1. Create a public repo named `dipeshbalani.github.io`.
2. Upload `index.html` and `Dipesh_Balani_Resume.pdf`.
3. Settings > Pages > Source: deploy from branch `main`, folder `/root`.
4. Live at https://dipeshbalani.github.io in about a minute.

## Custom domain
1. Buy dipeshbalani.com (Cloudflare Registrar, Porkbun, or Namecheap).
2. Repo Settings > Pages > Custom domain: dipeshbalani.com, then tick "Enforce HTTPS" once available.
3. At the registrar, add DNS records:
   - A records for @: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME for www: dipeshbalani.github.io
