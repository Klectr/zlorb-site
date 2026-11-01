# zlorb-site

Marketing site for [Zlorb](https://github.com/Klectr/zlorb) — the Linux daemon that makes `git push` the deploy.

Served at [zlorb.klectr.dev](https://zlorb.klectr.dev) from the Klectr VPS (`/var/www/zlorb`, nginx, TLS at Cloudflare).

## Editing

Two files, no build step: `index.html` and `mascot.webp`. Edit, commit, and copy both to the VPS:

```
scp index.html mascot.webp root@<vps>:/var/www/zlorb/
```
