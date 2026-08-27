# billadoesoftware.com

Public marketing site for **BILL-A-DOE SOFTWARE LLC**.

Served by GitHub Pages at the apex domain `billadoesoftware.com`.
The `CNAME` file in this repo is what claims that domain — do not delete it.

## Deploying a change
Edit `index.html`, commit, push to `main`. GitHub Pages redeploys automatically.

## DNS (managed at businessidentity.llc, NOT Cloudflare)
| record | name | value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | sgbilod.github.io |

⚠️ **Do not touch the MX or TXT/SPF records** — business email for
`admin@billadoesoftware.com` runs through businessidentity.llc and is
independent of this site.
