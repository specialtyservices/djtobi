===============================
DJTOBI.CH – GitHub Pages Setup
===============================

Project Repository:
-------------------
https://github.com/specialtyservices/djtobi

Hosting Platform:
-----------------
GitHub Pages (static site hosting, free)

Deployment Settings:
--------------------
Source: main branch
Folder: / (root)
Build: automatic on commit

Custom Domain:
--------------
Domain: djtobi.ch
CNAME file content: djtobi.ch
Status: DNS check successful
HTTPS: enforced (Let's Encrypt certificate active)

DNS Configuration at GoDaddy:
-----------------------------
Type | Name | Value | TTL
-----|------|--------|-----
A | @ | 185.199.108.153 | 1 hour
A | @ | 185.199.109.153 | 1 hour
A | @ | 185.199.110.153 | 1 hour
A | @ | 185.199.111.153 | 1 hour
CNAME | www | specialtyservices.github.io | 1 hour
(Do NOT delete system record "_domainconnect")

Mail Configuration:
-------------------
Email hosting: Gmail (unchanged)
MX records: remain exactly as configured in Google Workspace

Contact Section:
----------------
Replaced HTML form with direct mail link:
<a href="mailto:booking@djtobi.ch?subject=Anfrage%20über%20DJTobi.ch">Mail uns hier</a>

Notes:
------
- Site files: index.html + assets/
- Fully HTTPS-secured (🔒)
- Deployment cost: €0 / month
- No external tracking or form services used
- Maintenance: simply commit new HTML/image updates to main branch

Last verified:
--------------
26 October 2025
