# zlorb-site

Marketing site for [Zlorb](https://github.com/Klectr/zlorb) — the Linux daemon that makes `git push` the deploy.

Served at [zlorb.klectr.dev](https://zlorb.klectr.dev) from the Klectr VPS (`/var/www/zlorb`, nginx, TLS at Cloudflare).

## Editing

It is one self-contained file: `index.html`. Edit it, commit, and copy it to the VPS:

```
scp index.html root@<vps>:/var/www/zlorb/index.html
```

No build step, no dependencies.
