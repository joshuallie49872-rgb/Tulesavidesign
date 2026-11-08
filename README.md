# Tule Savi Design

Production website for Tule Savi Design, serving small businesses in Oregon and Washington.

- Bilingual English/Spanish pages
- Landscaping and contractor landing pages
- Static HTML/CSS/JS, hosted with GitHub Pages
- Custom domain: tulesavidesign.com
- Contact links currently go directly to saltonasbookkeeping@gmail.com until branded forwarding is verified

## Publish

1. GitHub repository Settings > Pages > Deploy from branch > main / root > Save.
2. GitHub repository Settings > Pages > Custom domain: tulesavidesign.com > Save.
3. At GoDaddy DNS, add A @ to each of GitHub's four addresses (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) and CNAME www to joshuallie49872-rgb.github.io.
4. Remove conflicting A/AAAA/CNAME records for the same host, without disturbing MX/TXT email records. Wait for DNS and SSL; enable Enforce HTTPS once available.

The CNAME file is included. Do not put login credentials in this public repository.
