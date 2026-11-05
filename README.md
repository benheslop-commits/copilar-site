# copilar-site

The public CoPILAR website. Built from `site/` in benheslop-commits/compilar (`python3 site/build.py`) and copied into `public/`; never edit `public/` by hand. Cloudflare Workers serves `public/` as static files (wrangler.jsonc) at copilar.group and conpilar.group, redeploying on every push to main.
