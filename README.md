# PrototypeDesign.no

## GitHub Pages

1. Repo → Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` / `/ (root)`
4. Save. Custom domain skal vise `prototypedesign.no` (filen `CNAME`).
5. Huk av Enforce HTTPS når sertifikatet er klart.

## DNS hos Domeneshop

Mine domener → prototypedesign.no → DNS-pekere → Vis avanserte innstillinger.

Slett gamle A-pekere mot webhotell først.

| Vertsnavn | Type | Data |
|---|---|---|
| *(tom)* | A | 185.199.108.153 |
| *(tom)* | A | 185.199.109.153 |
| *(tom)* | A | 185.199.110.153 |
| *(tom)* | A | 185.199.111.153 |
| *(tom)* | AAAA | 2606:50c0:8000::153 |
| *(tom)* | AAAA | 2606:50c0:8001::153 |
| *(tom)* | AAAA | 2606:50c0:8002::153 |
| *(tom)* | AAAA | 2606:50c0:8003::153 |
| www | CNAME | ole-arvid.github.io |
