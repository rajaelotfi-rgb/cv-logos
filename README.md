# cv-logos

Logo library used by the `cv-to-slide` skill. The skill clones this repo at the
start of each CV, uses the logos found here, and pushes any new logo it had to use.

| Folder | Content | Naming |
|---|---|---|
| `client/` | Companies, employers, clients | lowercase-with-hyphens.png |
| `tech/` | Technologies and tools | lowercase-with-hyphens.png |
| `cert/` | Certification badges | full certification name.png |
| `aliases.json`, `icon-aliases.json` | Alternative names → file name | |

Rules: PNG only, never overwrite an existing file, never add generic placeholder logos.
