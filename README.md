# Jelvan Ricolcol — Project Showcase Collection

Static showcase collection for selected applications. Each project has its own folder, demo login, dashboard preview, and project documentation.

## Projects

| Project | Showcase | Demo login | Dashboard | Production repository |
|---|---|---|---|---|
| BOLEKpad | [Open](./showcase/bolekpad/) | [Login](./showcase/bolekpad/login/) | [Dashboard](./showcase/bolekpad/dashboard/) | [Source](https://github.com/DevJel/Bolekpad) |
| Knowledge Center System | [Open](./showcase/knowledge-center/) | [Login](./showcase/knowledge-center/login/) | [Dashboard](./showcase/knowledge-center/dashboard/) | [Source](https://github.com/DevJel/knowledge-center-system) |
| JelHR — HR Information System | [Open](./showcase/hr-information-system/) | [Login](./showcase/hr-information-system/login/) | [Dashboard](./showcase/hr-information-system/dashboard/) | [Source](https://github.com/DevJel/jelhr-system) |
| Jels Kitchenwares | [Open](./showcase/jels-kitchenwares/) | [Login](./showcase/jels-kitchenwares/login/) | [Dashboard](./showcase/jels-kitchenwares/dashboard/) | Not verified |
| LeadMASTER | [Open](./showcase/leadmaster/) | [Login](./showcase/leadmaster/login/) | [Dashboard](./showcase/leadmaster/dashboard/) | [Source](https://github.com/DevJel/LeadMASTER) |
| Master AI — Multi-Agent Workspace | [Open](./showcase/master-ai/) | [Login](./showcase/master-ai/login/) | [Dashboard](./showcase/master-ai/dashboard/) | [Source](https://github.com/DevJel/xCoder-V2) |

## Structure

```text
showcase/
  bolekpad/
    index.html
    README.md
    login/index.html
    dashboard/index.html
  knowledge-center/
    index.html
    README.md
    login/index.html
    dashboard/index.html
  hr-information-system/
    index.html
    README.md
    login/index.html
    dashboard/index.html
  jels-kitchenwares/
    index.html
    README.md
    login/index.html
    dashboard/index.html
  leadmaster/
    index.html
    README.md
    login/index.html
    dashboard/index.html
  master-ai/
    index.html
    README.md
    login/index.html
    dashboard/index.html
assets/  # original screen assets used by the portfolio and dashboard previews
index.html
README.md
```

## Showcase limitations
- Login pages are simulated and local-only. They do not validate accounts, send OTPs, or store credentials.
- Dashboard pages reuse the original project screen assets available in the portfolio. They are visual previews, not live application dashboards.
- No production API, database, authentication provider, email service, cloud resource, or secret is connected.
- Private production repositories are linked for authorized access but their source code is not copied into this public repository.
- Source links are only included when repository identity was verified. Unverified projects are not assigned guessed URLs.

## Run locally
Open the root `index.html` for the existing portfolio or any `showcase/<project>/index.html`. The showcase is static HTML and requires no build process.

## Production references
- [Live portfolio introduction](https://jelvan-portfolio-introduction.pages.dev)
- [Original portfolio source](https://github.com/DevJel/Jelvan-R-Portfolio/tree/main/Portfolio%20Introduction)
- [This repository](https://github.com/DevJel/Portfolio_Version_4.0)

## Updating
Update the source project in its own repository first. Export an approved sanitized screen asset, replace the corresponding portfolio asset, and update the matching project README. Never publish production secrets or personal/customer records here.
